# Uso de Inteligência Artificial na produção de jogos na perspectiva da engenharia de software

1. Arthur Freitas Jardim

1. Thiago Andrade Ramalho

* Lesandro Ponciano (orientador de acadêmico)

## Introdução

1. A área da Engenharia de Software tratada neste trabalho é  _Inteligência Artificial para Jogos (Game_AI)_

1. O problema que este trabalho busca resolver nessa área é conforme as questões de pesquisa (RQ, do inglês Research Questions) a seguir: (RQ1) Quais são as técnicas de Engenharia de Software que podem ser aplicadas para otimizar a implementação de Inteligência Artificial na produção de jogos? (RQ2) Como a aplicação dessas técnicas influencia na eficiência do desenvolvimento de jogos com IA? (RQ3) Qual é o impacto dessas técnicas na qualidade do produto final em jogos que utilizam IA?

2. Resolver este problema é relevante porque a otimização da implementação de Inteligência Artificial na produção de jogos pode resultar em um desenvolvimento mais eficiente e na melhoria da qualidade do produto final. A aplicação adequada de técnicas de Engenharia de Software pode reduzir custos, acelerar o tempo de desenvolvimento e aumentar a satisfação dos jogadores através de experiências de jogo mais realistas e envolventes.

3. O objetivo geral deste trabalho é explorar como a aplicação de técnicas de Engenharia de Software pode otimizar a implementação de Inteligência Artificial na produção de jogos, focando na eficiência do desenvolvimento e na qualidade do produto final.

4. Os três objetivos específicos deste trabalho são: (1) Identificar e avaliar técnicas de Engenharia de Software que são eficazes na otimização da implementação de IA em jogos; (2) Analisar a influência dessas técnicas na eficiência do processo de desenvolvimento de jogos com IA; (3) Avaliar o impacto dessas técnicas na qualidade do produto final, considerando fatores como realismo, jogabilidade e satisfação dos jogadores.

## Fundamentação Teórica

1. O conceito/teoria principal associado a este trabalho é integração de inteligência artificial na engenharia de software. A sua definição neste trabalho é a "combinação sistemática de princípios, práticas e ferramentas da Engenharia de Software com técnicas e algoritmos de Inteligência Artificial para o desenvolvimento de software robusto, eficiente e de alta qualidade, com foco em jogos digitais", conforme definido no trabalho "Engineering AI-Powered Systems: A Software Engineering Perspective" (https://ieeexplore.ieee.org/document/9551634), pelos autores Ivan Peña-Arenas, Thierry Garaix, Philippe Lacomme, Nikolay Tchernev (2021). Este artigo destaca diversas técnicas de Engenharia de Software que são cruciais para a integração eficaz de IA, incluindo modelagem e design de software usando UML, gestão de configuração e controle de versão com ferramentas como Git, metodologias ágeis como Scrum e Kanban, práticas de testes de software como Test-Driven Development (TDD) e Behavior-Driven Development (BDD), refatoração de código, documentação de software, e análise e garantia de qualidade de software através de revisões de código e análises estática e dinâmica.

1. O conceito/teoria secundário associado a este trabalho é qualidade de software. A sua definição neste trabalho é "conjunto de atributos intrínsecos de um software que determinam sua capacidade de atender às necessidades dos usuários e stakeholders, incluindo confiabilidade, eficiência, segurança, manutenibilidade, portabilidade e usabilidade", conforme definido no trabalho "Software Quality Assurance: A Roadmap for the Future" (https://ieeexplore.ieee.org/document/9743014), pelos autores H Bhatt, Arvind Meniya (2022).

1. O conceito/teoria terciário associado a este trabalho é _metodologias de integração de inteligência artificial_ A sua definição neste trabalho é _"Conjunto estruturado de práticas, processos e ferramentas de Engenharia de Software que guiam a integração eficaz de algoritmos e sistemas de IA em projetos de software, otimizando o desenvolvimento e a qualidade do produto final, com ênfase em jogos digitais"_ Essa definição é conforme definido no trabalho "Software Engineering Practices for AI Integration: A Survey and Taxonomy" (https://ieeexplore.ieee.org/document/9803421), pelos autores M. B. Ryzhikov, V. N. Kovregin, Yu. A. Novikova (2022).

## Trabalhos Relacionados

1. O trabalho mais relacionado é "Exploring the Potential of A.I.-Driven Opponents in Video Games" (https://ieeexplore.ieee.org/document/9888909), publicado no ano 2020, porque ele fornece uma revisão abrangente sobre a aplicação de IA no desenvolvimento de jogos, destacando os principais desafios, oportunidades e tendências. Este estudo é relevante porque aborda diretamente a aplicação de IA em jogos, similar ao foco desta pesquisa.

1. O segundo trabalho mais relacionado é "Engineering Software for AI Integration: Best Practices and Case Studies" (https://doi.org/10.1145/3366423.3380273), publicado no ano 2021, porque ele investiga metodologias de Engenharia de Software aplicadas especificamente para integrar IA em diversos contextos, incluindo jogos. Este trabalho fornece uma base sólida sobre as melhores práticas e exemplos práticos, alinhando-se com os objetivos de desenvolver e avaliar metodologias de integração de IA.
   
1. O terceiro trabalho mais relacionado é "Assessing the Impact of AI on Game Quality: A Metric-Based Approach" (https://doi.org/10.1109/ICSE43902.2021.00059), publicado no ano 2021, porque ele avalia como a integração de IA afeta a qualidade dos jogos usando métricas de desempenho, usabilidade e manutenibilidade. Este estudo é pertinente porque fornece um framework para medir o impacto das metodologias propostas na qualidade do produto final, um dos objetivos específicos desta pesquisa.

## Materiais e Métodos

1. Este estudo adota uma abordagem "quantitativa" e "descritiva" para avaliar a integração de IA na Engenharia de Software aplicada ao desenvolvimento de jogos. A pesquisa envolverá a participação de 50 programadores durante um período de 6 meses. Esses programadores implementarão funcionalidades de IA em projetos de jogos, aplicando diversas técnicas de Engenharia de Software.

2. Os materiais e dados utilizados incluem 30 projetos de código aberto selecionados no GitHub com base no número de forks, variando de 10 a 10.000. Os dados dos commits dos programadores serão coletados via API do GitHub, incluindo informações sobre o projeto, o programador e a data do commit. Além disso, serão coletados dados sobre o número de forks e o número de programadores de cada projeto via API do GitHub.

3. As métricas de avaliação usadas no estudo serão a Relative Activity Duration, que avalia a duração relativa da atividade de um programador em um projeto; o Activity Ratio, que mede a proporção de tempo que um programador passa ativo em um projeto; o número de forks do projeto, como um indicador de popularidade e engajamento; e o número de programadores no projeto.

4. Os programadores aplicarão várias técnicas de Engenharia de Software, incluindo modelagem e design de software usando UML e Design Patterns; gestão de configuração e controle de versão com ferramentas como Git e práticas de CI/CD; metodologias ágeis como Scrum e Kanban; práticas de testes de software como TDD e BDD; refatoração de código para melhorar a legibilidade e manutenibilidade; documentação de software ágil e detalhada das APIs; e análise e garantia de qualidade através de revisões de código e análises estática e dinâmica.

5. Para garantir uma análise abrangente, serão selecionados jogos de diferentes gêneros e plataformas. Os métodos de análise estatística incluirão agrupamento K-Means, regressão linear, correlação (Spearman ou Kendall), e análise de tendência central e dispersão.

6. Serão conduzidos estudos de caso em empresas de desenvolvimento de jogos para aplicar e avaliar as metodologias desenvolvidas, identificando benefícios e desafios. As informações sobre o sucesso comercial dos jogos desenvolvidos serão obtidas de fontes públicas como relatórios financeiros, dados de vendas e análises de mercado disponíveis em plataformas como Steam e App Store. O sucesso comercial será analisado em relação às técnicas de Engenharia de Software aplicadas durante o desenvolvimento dos jogos, permitindo avaliar como essas práticas influenciam o desempenho comercial e a qualidade final do produto.
