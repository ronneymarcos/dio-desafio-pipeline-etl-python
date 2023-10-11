<div align="center">
<img src="https://hermes.digitalinnovation.one/assets/diome/logo-full.svg" alt="Logo Bootcamp" width="80">
<h1>Santander Bootcamp 2023 <br> Ciência de Dados com Python</h1>
<img src="https://hermes.dio.me/tracks/03253ff0-95b9-4904-84e7-2063e9d6cb26.png" alt="Logo Bootcamp" width="220">
</div>
 
 <h1 align="center"> 🎲 Construindo um Pipeline ETL com Python 🐍  - Analisando Desempenho de Escola no ENEM</h1>

Este é um desafio de projeto do **Santander Bootcamp 2023 - Ciência de Dados com Python.** 

O projeto proposto toma como base o modelo proposto pela Dio, intitulado **Explorando IA Generativa em um Pipeline de ETL com Python**.</br>
Acesse aqui o notebook do projeto modelo da Dio: <a target="_blank" href="https://colab.research.google.com/drive/1SF_Q3AybFPozCcoFBptDSFbMk-6IVGF-?usp=sharing">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

# 👨🏽‍💻 Meu projeto

**Contexto**: Meu desafio é criar uma pipeline ETL para extrair dados de um arquivo CSV disponibilizado por uma escola de ensino médio que gostaria de ter informações sobre o seu desempenho nos últimos 5 anos (2018-2022) no Exame Nacional do Ensino Médio (ENEM).<br/>
Feita a **Extração dos dados**, passarei para a fase de **Transformação**, na qual vou precisar calcular a média das notas disponibilizadas por área do conhecimento (Linguagens, Humanas, Natureza e Matemática).<br/>
Por fim, devo realizar o **Carregamento do dados** transformados em um novo arquivo CSV, além de criar uma visualização gráfica dos resultados.

# 📋 Etapas do Pipeline de ETL

## ⛏️ Extract
Nesta etapa, vamos extrair os dados de resultados por área de conhecimento do arquivo CSV **dados-enem.csv**. Este arquivo traz informações referentes aos resultados da escola nos últimos 5 anos (2018-2022). As colunas contidas no arquivo são as seguintes: **Área** e **Média por ano**.

## 🎲 Transform
Agora que já temos os dados carregados na fase de Extração, podemos calcular a média de cada área do conhecimento nos últimos 5 anos usando a função **mean( )** do pandas.

## 📊 Load
Nessa etapa vamos salvar os dados transformados em um novo arquivo CSV e criar um gráfico que possa ser visualizado em tela. Para isso, vou utilizar a biblioteca **Matplotlib** do pandas.

# 🧰 Ferramentas utilizadas

![PYTHON](https://img.shields.io/badge/Python-3776AB.svg?style=for-the-badge&logo=Python&logoColor=white)
![GIT](https://img.shields.io/badge/Git-F05032.svg?style=for-the-badge&logo=Git&logoColor=white)
![GOOGLE COLAB](https://img.shields.io/badge/Google%20Colab-F9AB00.svg?style=for-the-badge&logo=Google-Colab&logoColor=white)
![VSCODE](https://img.shields.io/badge/Visual%20Studio%20Code-007ACC.svg?style=for-the-badge&logo=Visual-Studio-Code&logoColor=white)

# 🔗 Confira meu projeto no Google Colab
<a target="_blank" href="https://colab.research.google.com/drive/1qwz1d6T6c64Mc0VCYbBY1do9-dL9UPrG#scrollTo=kNuP0SDUZMBY">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>