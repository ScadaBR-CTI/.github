<div align="justify">
  
# ScadaBR-CTI | Monitoramento e Eficiência Energética

Este repositório documenta o desenvolvimento do projeto ScadaBR-CTI, que integra automação e análise de dados operacionais no CTI Renato Archer.

O sistema trabalha com dados provenientes do ScadaBR e pode abrigar tanto informações em tempo real quanto bases históricas, permitindo diferentes formas de análise conforme a disponibilidade dos dados.

No caso atual, o foco está na utilização de dados históricos, que são estruturados, tratados e analisados em R para geração de indicadores e visualizações. Isso possibilita estudar o comportamento de variáveis operacionais ao longo do tempo, como consumo energético, desempenho de equipamentos e padrões de funcionamento.

O projeto é voltado ao monitoramento de infraestrutura crítica e à análise de eficiência energética, permitindo identificar tendências, variações e possíveis anomalias mesmo em contextos sem atualização contínua de dados.

O objetivo é demonstrar como tanto dados em tempo real quanto bases históricas podem ser aproveitados como ferramenta de análise e apoio à tomada de decisão técnica, contribuindo para a melhoria contínua da operação no CTI. O banco de dados possui um repositório próprio, dedicado à sua documentação.

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
* **[Análise de Dados](https://github.com/ScadaBR-CTI/analise-dados-r)**: Os dados foram submetidos a uma análise gráfica, com integrações de Linguagem R.

---
*Este é um sistema ciberfísico em constante evolução para suporte à tomada de decisão energética.*
</div>
