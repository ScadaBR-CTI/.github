# ScadaBR-CTI | Monitoramento e Eficiência Energética

Bem-vindo ao repositório de dados, automação e inteligência operacional do projeto ScadaBR-CTI. Este espaço reúne soluções para monitoramento de infraestrutura crítica, análise operacional e eficiência energética no CTI Renato Archer.

O projeto integra sistemas supervisórios, banco de dados e ferramentas analíticas para acompanhar, em tempo real, o funcionamento de ativos essenciais.

Seu objetivo é transformar dados operacionais em informações úteis, apoiando decisões técnicas, identificando tendências, antecipando falhas e promovendo melhoria contínua da operação.

**[Visão Geral](https://github.com/ScadaBR-CTI/Documenta-o.md)**: Neste link é possivél encontrar uma documentação completa com todos os medidores abordados e o diagrama de blocos.

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
