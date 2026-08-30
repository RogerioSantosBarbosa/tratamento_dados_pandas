# Análise Exploratória e Limpeza de Dados de Vendas com Pandas

Projeto de engenharia e limpeza de dados focado em transformar uma base de vendas corrompida em uma fonte confiável para análise. Gerei uma base sintética de 100 pedidos com problemas típicos de dados reais — valores ausentes, duplicatas, tipos incorretos e outliers — e apliquei um fluxo completo de diagnóstico, tratamento e engenharia de atributos com Pandas e NumPy.

## O que o notebook cobre

1. **Diagnóstico** — inspeção de tipos, valores nulos e duplicatas antes de qualquer alteração.
2. **Tratamento de dados ausentes** — imputação por mediana (`Quantidade`) e moda (`Status_Entrega`); remoção de linhas onde o dado não podia ser inferido (`Cliente_ID`, `Preco_Unitario`).
3. **Correção de tipos** — conversão de colunas numéricas armazenadas como texto, com tratamento de valores inválidos via `errors='coerce'`.
4. **Remoção de duplicatas e outliers** — outliers identificados pela regra de 3 desvios-padrão.
5. **Engenharia de atributos e análise** — cálculo de faturamento total, por categoria e por produto, e evolução de vendas ao longo do tempo.

## Tecnologias

Python 3 · Pandas · NumPy · Matplotlib · Seaborn · Jupyter Notebook

## Como executar

\`\`\`bash
git clone https://github.com/RogerioSantosBarbosa/analise-dados-vendas-pandas.git
pip install -r requirements.txt
\`\`\`

Abra `tratamento_dados_pandas.ipynb` no Jupyter Lab ou VS Code e execute as células.