# Projeto: Pipeline de Engenharia de Dados com Apache NiFi, PostgreSQL e Metabase

Este projeto é um pipeline de dados completo que utiliza Apache NiFi para ingestão e transformação de dados públicos, PostgreSQL como banco de dados relacional para armazenamento e Metabase como ferramenta de visualização interativa.
## Tecnologias utilizadas

# Diagrama
![Diagrama](https://github.com/user-attachments/assets/8ef2e76d-2c69-43e2-b3d4-f7120a7350c8)



    Apache NiFi: Para orquestração e automação do fluxo de dados.

    Pentaho:  Integração e transformação dos dados para preparação e carregamento.

    PostgreSQL: Armazenamento estruturado dos dados processados.

    Metabase: Visualização e análise dos dados com dashboards.
    
    Docker & Docker Compose: Para orquestrar e isolar os serviços em containers.

## Objetivo

Demonstrar um fluxo típico de engenharia de dados que simula um ambiente real, usando dados públicos (ex: IBGE, dados.gov.br, etc), extraídos, tratados e carregados em um banco relacional, com visualizações construídas a partir desses dados.
##📦 Estrutura do projeto
```
├── docker-compose.yml
├── nifi/
│   └── templates/
│       └── pipeline.xml (template do fluxo no NiFi)
├── metabase/
│   └── ...
├── postgres/
│   └── init.sql (criação de tabelas e schemas)
└── dados/
    └── arquivos.csv (dados públicos utilizados)
```

## Como rodar o projeto
docker-compose up -d
