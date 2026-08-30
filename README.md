# Análise Exploratória e Limpeza de Dados de Vendas com Pandas 🛒

Um projeto prático de engenharia de dados e EDA (Exploratory Data Analysis) focado em saneamento de bases corrompidas, tratamento de valores ausentes e extração de insights de negócio.

## 🎯 O Problema de Negócio
Muitas empresas acumulam grandes volumes de dados transacionais, mas sofrem com baixa qualidade de armazenamento (dados ausentes, tipos incorretos, duplicatas e outliers). O objetivo deste projeto foi atuar na limpeza profunda de um dataset de e-commerce e na engenharia de atributos utilizando a biblioteca Pandas, transformando um ambiente caótico em uma fonte confiável para tomada de decisão.

## 💻 Tecnologias Utilizadas
* **Python 3**
* **Pandas & NumPy** (Manipulação, limpeza, tratamento de nulos e engenharia de dados)
* **Seaborn & Matplotlib** (Visualização e gráficos analíticos)
* **Jupyter Notebook** (Documentação e storytelling interativo)

## 📊 Principais Etapas do Projeto
1. **Diagnóstico Estrutural:** Identificação de tipos de dados incorretos e colunas corrompidas (ex: valores monetários salvos como texto).
2. **Tratamento de Dados Ausentes:** Imputação e tratamento estratégico de valores nulos (`NaN`).
3. **Remoção de Duplicatas e Outliers:** Filtragem de registros repetidos e correção de anomalias estatísticas nas quantidades e preços.
4. **Análise Exploratória (EDA):** Geração de gráficos para avaliar o comportamento das vendas, categorias mais lucrativas e eficiência logística.

> *Para explorar o código comentado passo a passo e visualizar os gráficos gerados, abra o arquivo `tratamento_dados_pandas.ipynb`.*

## 🚀 Como Executar Localmente

1. Clone este repositório:
   ```bash
   git clone [https://github.com/rogerio-portfolio-pessoal/analise-dados-vendas-pandas.git](https://github.com/rogerio-portfolio-pessoal/analise-dados-vendas-pandas.git)

2. Instale as dependências:
    ```bash
    pip install -r requirements.txt

3. Abra o arquivo .ipynb no VSCode e execute as células.
   