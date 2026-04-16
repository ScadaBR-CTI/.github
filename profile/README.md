# ScadaBR-CTI | Monitoramento e Eficiência Energética

Bem-vindo ao repositório central de gerenciamento de dados e automação. Este projeto é dedicado à supervisão de infraestrutura crítica e otimização do consumo de energia.

## Escopo do Projeto
O sistema integra a coleta de dados industriais com análise estatística avançada para garantir a estabilidade e eficiência de:
* **Infraestrutura:** Datacenters, transformadores e sistemas de refrigeração (Chillers).
* **Monitoramento:** Gestão de mais de 100 pontos de sensores.
* **Gestão:** Automação de relatórios de economia contratual e indicadores de performance.

## Stack Tecnológica
* **Supervisão:** [ScadaBR](http://www.scadabr.com.br) / [ScadaLTS](https://scada-lts.com.br) para interface homem-máquina e telemetria.
* **Banco de Dados:** MySQL 8.0 / MariaDB para armazenamento de séries temporais.
* **Análise de Dados:** Linguagem **R** (utilizando `dplyr`, `lubridate` e `ggplot2`) para perfis de carga e detecção de anomalias.
* **Automação de Relatórios:** VBA para integração automática com Excel e Outlook.

## Estrutura de Repositórios
* **/analise-r**: Scripts para processamento de curvas de carga e gráficos térmicos.
* **/database-sql**: Queries de configuração, criação de tabelas e manutenção do histórico.
* **/automacao-vba**: Ferramentas de exportação de relatórios em PDF e envio de e-mails.

---
*Este é um sistema ciberfísico em constante evolução para suporte à tomada de decisão energética.*
