# 📊 Análise de Recursos Humanos - People Analytics

[![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)](https://www.microsoft.com/excel) [![Power Query](https://img.shields.io/badge/Power_Query-F2C811?style=for-the-badge&logo=power-bi&logoColor=black)](https://powerquery.microsoft.com/) ![PowerPoint](https://img.shields.io/badge/Microsoft%20PowerPoint-B7472A?style=for-the-badge&logo=microsoft-powerpoint&logoColor=white)

## 🎯 Visão Geral

Este projeto oferece uma análise estratégica do quadro de funcionários de uma empresa para gerar insights estratégicos e apoiar decisões de RH com People Analytics.

## 📋 **[Ver Relatório](reports/rh_relatorio.pdf)**

> **Relatório analítico de RH sobre composição da equipe, desempenho, satisfação, recrutamento e salários, com recomendações para reduzir desligamentos e fortalecer a gestão da equipe.**

## 🏗️ Arquitetura da Solução  

```mermaid
graph LR
    subgraph Input ["📥 DADOS DE ENTRADA"]
        A["db_rh.xlsx<br/>💼 Dados de RH"]
    end

    subgraph ETL ["⚙️ ETL"]
        B["Power Query (Linguagem M)<br/>Tratamento de Dados"]
    end

    subgraph Output ["📈 RESULTADOS"]
        C["Relatório Analítico<br/>Excel"]
        D["Relatório<br/>PDF"]
        E["Apresentação<br/>PowerPoint"]
    end

    A --> B
    B --> C
    B --> D
    B --> E

    %% Grupos com bordas mais suaves
    style Input fill:#F8FFFE,stroke:#34495E,stroke-width:2px,color:#2C3E50
    style ETL fill:#FFF8E7,stroke:#E67E22,stroke-width:2px,color:#D35400
    style Output fill:#F0F8FF,stroke:#3498DB,stroke-width:2px,color:#1565C0
    
    %% Dados de entrada em cinza neutro
    style A fill:#7F8C8D,stroke:#5D6D7E,stroke-width:2px,color:#FFFFFF
    
    %% Processamento em laranja vibrante
    style B fill:#E67E22,stroke:#D35400,stroke-width:3px,color:#FFFFFF
    
    %% Saídas em tons de azul e verde
    style C fill:#2E86C1,stroke:#1B4F72,stroke-width:3px,color:#FFFFFF
    style D fill:#27AE60,stroke:#229954,stroke-width:3px,color:#FFFFFF
    style E fill:#B7472A,stroke:#943126,stroke-width:3px,color:#FFFFFF
```

## 📁 Estrutura do Projeto

```text
people_analytics_excel/
│
├── data/
│   └── raw/                         # Dados brutos
│       └── db_rh.xlsx
│
├── reports/                         # Relatórios
│   ├── rh_analises_v1.0.xlsx
│   ├── rh_relatorio.pdf
│   └── rh_apresentacao_v1.pptx
│
├── assets/                          # Recursos visuais
│   ├── 1_slide_apresentacao.png
│   ├── 2_slide_apresentacao.png
│   ├── 3_slide_apresentacao.png
│   ├── 4_slide_apresentacao.png
│   ├── 5_slide_apresentacao.png
│   └── 6_slide_apresentacao.png
│
├── docs/                            # Documentação
│   └── dicionario_dados.md
│
└── README.md
```

## 📚 Documentação e Recursos

| Recurso | Descrição | Link |
|---------|-----------|------|
| 📊 **Planilha de Análises** | Arquivo Excel com  as análises realizadas para suporte às respostas | [rh_analises_v1.0.xlsx](reports/rh_analises_v1.0.xlsx) |
| 📋 **Relatório** | Documento em PDF com as respostas | [rh_relatorio.pdf](reports/rh_relatorio.pdf) |
| 🎨 **Apresentação** | Arquivo PowerPoint para stakeholders | [rh_apresentacao_v1.pptx](reports/rh_apresentacao_v1.pptx) |
| 📖 **Dicionário de Dados** | Documento técnico com definições e especificações dos campos de dados | [dicionario_dados.md](docs/dicionario_dados.md) |
