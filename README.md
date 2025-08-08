# Análise de Churn em Dados de Telecomunicações

Este projeto tem como objetivo analisar o comportamento dos clientes de uma empresa de telecomunicações para identificar fatores que influenciam a evasão (Churn). Utilizando dados reais fornecidos em formato JSON, realizamos a extração, transformação, análise exploratória e geração de insights.

## Estrutura do Projeto

- **data/**: Dados brutos em formato JSON.
- **notebooks/**: Notebook Jupyter com todo o código de análise e gráficos.
- **scripts/**: Scripts Python para extração, transformação e análise.
- **reports/**: Relatórios em Markdown e PDF com as conclusões do estudo.

## Principais Etapas

1. Extração e normalização dos dados JSON.
2. Tratamento de valores faltantes e conversão de tipos.
3. Criação de variáveis derivadas, como `Contas_Diarias`.
4. Análise estatística descritiva e visualizações.
5. Identificação dos principais fatores relacionados ao churn.

## Principais Insights

- Clientes com contratos mensais apresentam maior índice de churn.
- Serviços de internet Fiber optic estão associados a maior evasão.
- Métodos de pagamento automáticos têm menor taxa de cancelamento.

## Tecnologias Utilizadas

- Python 3
- Pandas
- Matplotlib e Seaborn
- Jupyter Notebook

## Como Executar

1. Clone este repositório:
```bash
git clone https://github.com/seu-usuario/telecom-churn-analysis.git
