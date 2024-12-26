# Gerenciador de Relatórios de Vendas

Ferramenta de relatórios self-service para análise de dados de fabricação e vendas de consoles em mercados globais.

## 📊 Sobre o Projeto

Esta ferramenta processa e analisa dados CSV de distribuidores terceirizados para gerar insights acionáveis para otimização da fabricação.

### Contexto do Negócio

- Empresa focada exclusivamente na fabricação de consoles
- Produtos distribuídos e vendidos globalmente através de parceiros
- Dados brutos armazenados em formato CSV em `data/raw_data/`

## 🎯 Objetivos

- Consolidar e normalizar dados de vendas de terceiros
- Transformar dados de vendas em insights úteis para fabricação
- Identificar produtos com melhor desempenho por país
- Otimizar transporte e logística desde a fabricação até o ponto de venda

## 📁 Estrutura do Projeto Ideal

```
sales-report-manager/
├── data/
│   ├── raw_data/        # Dados brutos em CSV
│   └── processed/       # Dados processados e normalizados
├── src/
│   ├── analysis/        # Módulos de análise de dados
│   ├── processing/      # Scripts de processamento
│   └── utils/           # Funções auxiliares
├── reports/
│   ├── monthly/         # Relatórios mensais
│   └── quarterly/       # Relatórios trimestrais
├── tests/               # Testes unitários e de integração
└── docs/                # Documentação adicional
```

## 📈 Principais Funcionalidades

- Ingestão automatizada de dados CSV
- Consolidação de dados de múltiplas fontes
- Análise geográfica de vendas
- Métricas de desempenho de produtos
- Insights para otimização logística

## 🚀 Como Começar

1. Coloque seus arquivos CSV no diretório `data/raw_data/`
2. Execute a ferramenta de análise (instruções serão adicionadas)
3. Acesse os relatórios gerados no diretório `reports/`

## 📝 Observação

Este projeto faz parte do desafio do Bootcamp Microsoft AI for Tech, com foco na criação de soluções inteligentes de análise de dados.
