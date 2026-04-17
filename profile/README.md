# ScadaBR-CTI | Monitoramento e Eficiência Energética

Bem-vindo ao repositório central de dados, automação e inteligência operacional do projeto ScadaBR-CTI. Este espaço foi desenvolvido para reunir soluções voltadas ao monitoramento de infraestrutura crítica, à análise do desempenho operacional e à busca constante por eficiência energética no CTI Renato Archer. 
Mais do que simplesmente armazenar informações, este projeto busca transformar os dados gerados nas operações do CTI Renato Archer em conhecimento útil e confiável, contribuindo para decisões mais ágeis, assertivas e estratégicas. O projeto reúne sistemas supervisórios, banco de dados e ferramentas analíticas para acompanhar, em tempo real, o funcionamento de ativos essenciais no ambiente do CTI Renato Archer. 
A ideia é conectar tecnologia operacional e análise de dados em uma estrutura integrada, facilitando a visualização dos processos, reduzindo desperdícios e contribuindo para a melhoria contínua da operação. Com essa integração, fica mais fácil identificar tendências, antecipar possíveis falhas, comparar desempenhos ao longo do tempo e apoiar ações corretivas ou preventivas com base em informações confiáveis.

## Escopo do Projeto
O sistema atua em diferentes frentes da operação e foi estruturado para atender demandas técnicas e gerenciais relacionadas à infraestrutura do CTI Renato Archer:
* **Infraestrutura:** Datacenters, transformadores e sistemas de refrigeração (Chillers).
* **Monitoramento:** Gestão de mais de 100 pontos de sensores.
* **Gestão:** Automação de relatórios de economia contratual e indicadores de performance.

## Tecnologias Utilizadas
* **Supervisão:** [ScadaBR](http://www.scadabr.com.br) / [ScadaLTS](https://scada-lts.com) para interface homem-máquina e telemetria.
* **Banco de Dados:** MySQL 8.0 para armazenamento de séries temporais.
* **Análise de Dados:** Linguagem **R** (Principais bibliotecas: `dplyr`, `lubridate`, `ggplot2` e `plotly`) para perfis de carga e detecção de anomalias.
* **Automação de Relatórios:** Gráficos interativos, usando app Shiny.

## Estrutura de Repositórios
* **[Banco de Dados](https://github.com/ScadaBR-CTI/BANCO_DE_DADOS.md)**: Armazenamento, técnicas de recuperação e tratamento de dados.


---
*Este é um sistema ciberfísico em constante evolução para suporte à tomada de decisão energética.*
