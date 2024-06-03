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

1. O trabalho mais relacionado é "How Gamification Affects Software Developers: Cautionary Evidence from a Natural Experiment on GitHub" (https://doi.org/10.1109/ICSE43902.2021.00058), publicado no ano 2021, por que ele estuda como programadores que atuam em código aberto respondem à gamificação, que é uma forma de engajá-los e de mantê-los engajados.

1. O segundo trabalho mais relacionado é "Studying Software Developer Expertise and Contributions in Stack Overflow and GitHub" (https://doi.org/10.1109/ICSME46990.2020.00038), publicado no ano 2020, por que ele trata da expertise dos programadores e de suas contribuições em projetos de código aberto, permitindo entender suas contribuições em termos quantitativos e qualitativos, que são essenciais para análise de engajamento.

1. O terceiro trabalho mais relacionado é "Herding a Deluge of Good Samaritans: How GitHub Projects Respond to Increased Attention" (https://doi.org/10.1145/3366423.3380272), publicado no ano 2021,  por que ele coloca a questão da popularidade ou atenção recebida pelo projeto e de como isso afeta o comportamento dos programadores, sendo, portanto, relevante para se compreender como popularidade e engajamento podem estar relacionados.
## Materiais e Métodos

1. O tipo de pesquisa adotado neste trabalho é "quantitativa", porque _ela trata de atribuidos quantitativos associados à duração do engajamento dos programadores nos projetos_, e também é  e "descritiva", pois ela _trata da descrição das propriedades do engajamento natural (orgânico) dos programadores sem qualquer controle de variáveis._

1. Os materiais utilizados neste trabalho são come segue: a) _projetos de código aberto selecionados são aqueles que utilizam a plataforma GitHub (https://github.com/), um conjunto de 30 projetos com diferente número de forks, de 10 a 10000, são analisados; 2) dados dos commits feitos pelos programadores são coletados via Interface de Programação de Aplicações (API) do GitHub (https://docs.github.com/en/rest?apiVersion=2022-11-28). A cada commit estão associadas às informações do projeto, programador e data; 3) dados da popularidade dos projetos quanto ao número de forks e número de programadores, ambos coletados via API._

1. Os métodos empregados neste trabalho são _agrupamento k-means (https://doi.org/10.1016/S0031-3203(02)00060-2), regressão linear, correlação (Spearman ou Kendall), análise de tendência central e de dispersão._

1. As métricas de avaliação empregadas no estudo são _Relative Activitiy Duration_ do programador (https://doi.org/10.15346/hc.v1i2.12), _Activity Ratio_ do programador (https://doi.org/10.1109/MCSE.2014.4), _número de forks_ do projeto e número de programadores no projeto. 

1. As etapa de execução do trabalho são: (1) coletar os dados dos projetos no GitHub; (2) calcular as métricas, (3) analisar tendência central e dispersão; (4) analisar a relação entre as variáveis por correlação e regressão; e (5) analisar o agrupamento k-means. A partir dessas etapas, as questões de pesquisa são respondidas e os objetivos (geral e específicos) são atingidos.
