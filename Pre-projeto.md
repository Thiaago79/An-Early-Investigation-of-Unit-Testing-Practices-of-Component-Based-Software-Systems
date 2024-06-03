# Uso de Inteligência Artificial na produção de jogos

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

1. O conceito/teoria principal associado a este trabalho é _integração de inteligência artificial na engenharia de software._  A sua definição neste trabalho é a "combinação sistemática de princípios, práticas e ferramentas da Engenharia de Software com técnicas e algoritmos de Inteligência Artificial para o desenvolvimento de software robusto, eficiente e de alta qualidade, com foco em jogos digitais", conforme definido no trabalho "Engineering AI-Powered Systems: A Software Engineering Perspective" (https://ieeexplore.ieee.org/document/9551634), pelos autores Ivan Peña-Arenas, Thierry Garaix, Philippe Lacomme, Nikolay Tchernev (2021).

1. O conceito/teoria secundário associado a este trabalho é _qualidade de software_. A sua definição neste trabalho é "conjunto de atributos intrínsecos de um software que determinam sua capacidade de atender às necessidades dos usuários e stakeholders, incluindo confiabilidade, eficiência, segurança, manutenibilidade, portabilidade e usabilidade", conforme definido no trabalho "Software Quality Assurance: A Roadmap for the Future" (https://ieeexplore.ieee.org/document/9743014), pelos autores H Bhatt, Arvind Meniya (2022).

1. O conceito/teoria terciário associado a este trabalho é _metodologias de integração de inteligência artificial_ A sua definição neste trabalho é _"Conjunto estruturado de práticas, processos e ferramentas de Engenharia de Software que guiam a integração eficaz de algoritmos e sistemas de IA em projetos de software, otimizando o desenvolvimento e a qualidade do produto final, com ênfase em jogos digitais"_ Essa definição é conforme definido no trabalho "Software Engineering Practices for AI Integration: A Survey and Taxonomy" (https://ieeexplore.ieee.org/document/9803421), pelos autores M. B. Ryzhikov, V. N. Kovregin, Yu. A. Novikova (2022).

## Trabalhos Relacionados

1. O trabalho mais relacionado é "Exploring the Potential of A.I.-Driven Opponents in Video Games" (https://ieeexplore.ieee.org/document/9888909), publicado no ano 2020, porque ele fornece uma revisão abrangente sobre a aplicação de IA no desenvolvimento de jogos, destacando os principais desafios, oportunidades e tendências. Este estudo é relevante porque aborda diretamente a aplicação de IA em jogos, similar ao foco desta pesquisa.

1. O segundo trabalho mais relacionado é "Engineering Software for AI Integration: Best Practices and Case Studies" (https://doi.org/10.1145/3366423.3380273), publicado no ano 2021, porque ele investiga metodologias de Engenharia de Software aplicadas especificamente para integrar IA em diversos contextos, incluindo jogos. Este trabalho fornece uma base sólida sobre as melhores práticas e exemplos práticos, alinhando-se com os objetivos de desenvolver e avaliar metodologias de integração de IA.
   
1. O terceiro trabalho mais relacionado é "Assessing the Impact of AI on Game Quality: A Metric-Based Approach" (https://doi.org/10.1109/ICSE43902.2021.00059), publicado no ano 2021, porque ele avalia como a integração de IA afeta a qualidade dos jogos usando métricas de desempenho, usabilidade e manutenibilidade. Este estudo é pertinente porque fornece um framework para medir o impacto das metodologias propostas na qualidade do produto final, um dos objetivos específicos desta pesquisa.
1. O tipo de Pesquisa adotado neste estudo é mista, combinando elementos de pesquisa quantitativa e qualitativa.
Quantitativa: Análise de dados quantitativos relacionados ao engajamento dos programadores.
Qualitativa: Exploração e descrição das características do engajamento natural dos programadores.

2. Os materiais utilizados neste trabalho são os seguintes:
a) plataformas de desenvolvimento de jogos como Unity (https://unity.com/) e Unreal Engine (https://www.unrealengine.com/), que são amplamente utilizadas na indústria para a criação de jogos com IA;
b) conjuntos de dados de benchmarks de IA em jogos, como os disponibilizados pelo AI and Games Research Network (http://www.aiandgames.com/);
c) ferramentas de análise e desenvolvimento de IA, incluindo bibliotecas de aprendizado de máquina como TensorFlow (https://www.tensorflow.org/) e PyTorch (https://pytorch.org/);
d) dados de desempenho e qualidade dos jogos, coletados a partir de plataformas de distribuição de jogos, análises de usuários e métricas de uso das APIs de IA.

3. Os métodos empregados neste trabalho são análise de regressão linear para determinar a relação entre as técnicas de Engenharia de Software e a eficiência do desenvolvimento de jogos; análise de correlação (Spearman ou Pearson) para examinar a relação entre a aplicação das técnicas de IA e a qualidade do produto final; e métodos de agrupamento k-means para categorizar os projetos de jogos com base em características de desenvolvimento e desempenho.

4. As métricas de avaliação empregadas no estudo são tempo de desenvolvimento (medido em horas ou dias), número de commits no repositório do projeto, taxa de bugs (número de bugs reportados por linha de código), desempenho do jogo (FPS - frames por segundo), satisfação do usuário (avaliada por meio de classificações e comentários), e sucesso comercial (medido por vendas e downloads).

5. As etapas de execução do trabalho são:(1) coletar dados dos projetos de jogos que utilizam IA, incluindo informações de desenvolvimento e desempenho; (2) calcular as métricas de avaliação mencionadas; (3) realizar análises de tendência central e dispersão das métricas coletadas; (4) analisar a relação entre as variáveis por meio de correlação e regressão; (5) aplicar o método de agrupamento k-means para identificar padrões e categorias de projetos de jogos.

A partir dessas etapas, as questões de pesquisa são respondidas e os objetivos (geral e específicos) são atingidos.
