# ScadaBR-CTI | Monitoramento e Eficiência Energética

Este repositório documenta o desenvolvimento do projeto ScadaBR-CTI, que integra automação e análise de dados operacionais no CTI Renato Archer. Esse sistema trabalha com dados provenientes do ScadaBR e pode abrigar tanto informações em tempo real quanto bases históricas, permitindo diferentes formas de análise conforme a disponibilidade dos dados.

No caso atual, o foco está na utilização de dados históricos, que são estruturados, tratados e analisados em R para geração de indicadores e visualizações. Isso possibilita estudar o comportamento de variáveis operacionais ao longo do tempo, como consumo energético, desempenho de equipamentos e padrões de funcionamento.

O objetivo é demonstrar como tanto dados em tempo real quanto bases históricas podem ser aproveitados como ferramenta de análise e apoio à tomada de decisão técnica, contribuindo para a melhoria contínua da operação no CTI. O banco de dados possui um repositório próprio, dedicado à sua documentação.

**[Documentação](https://github.com/ScadaBR-CTI/Documenta-o.md)**: Neste link é possivél encontrar uma documentação completa com todos os medidores abordados e o diagrama de blocos.

## Escopo do Projeto
O projeto contempla a organização e análise de dados operacionais provenientes do ScadaBR, utilizando ferramentas em R para tratamento, modelagem e visualização das informações.

O escopo inclui o desenvolvimento de indicadores, análises temporais e dashboards voltados ao acompanhamento operacional e energético da infraestrutura monitorada, além da consolidação de uma base estruturada para futuras expansões e integrações analíticas.

## Tecnologias Empregadas
* **Sistema supervisório:** [ScadaBR](http://www.scadabr.com.br) plataforma para interface homem-máquina (IHM), aquisição de dados e telemetria operacional.
* **Banco de Dados:** MySQL 8.0 utilizado para armazenamento e organização das séries temporais provenientes do sistema supervisório.
* **Análise de Dados:** desenvolvimento das análises em linguagem R, utilizando o ambiente RStudio e bibliotecas como `dplyr`, `lubridate`, `ggplot2` e `plotly` para tratamento de dados, análise temporal e geração de perfis de carga.
* **Visualização e Relatórios:** utilização do Shiny para construção de dashboards e gráficos interativos voltados ao acompanhamento operacional e energético.

## Estrutura de Repositórios
* **[Banco de Dados](https://github.com/ScadaBR-CTI/BANCO_DE_DADOS.md)**: Armazenamento, técnicas de recuperação e tratamento de dados.
  
* **[Análise de Dados](https://github.com/ScadaBR-CTI/analise-dados-r)**: Os dados foram submetidos a uma análise gráfica, com integrações de Linguagem R.

---
*Este projeto constitui um sistema ciberfísico em constante evolução, desenvolvido para apoiar a análise operacional e a tomada de decisão energética a partir da integração entre monitoramento, processamento e interpretação de dados..*
