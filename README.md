# 📊 ETL e Análise de Dados de Deputados

## 🎯 Objetivo do Projeto
Este projeto foi desenvolvido como parte do meu portfólio em Análise de Dados. O objetivo principal foi estruturar um pipeline
de ETL (Extração, Transformação e Carga) para coletar dados públicos da API de Dados Abertos da Câmara dos Deputados, realizar 
o tratamento dessas informações e gerar insights sobre a gestão desses dados públicos.

## 🛠️ Tecnologias Utilizadas
* **Linguagem:** Python
* **Bibliotecas de Manipulação de Dados:** Pandas **Requests
* **Banco de Dados Local:** SQLite (arquivo `dados_abertos.bd`)
* **Ambiente de Desenvolvimento:** Jupyter Notebook

## ⚙️ Arquitetura do Pipeline (ETL)
1. **Extração (Extract):** Coleta automatizada de dados brutos sobre os deputados através de Python.
2. **Transformação (Transform):** Limpeza de dados com Pandas, tratando valores ausentes, nulos e divergentes, aplicando tipagem correta de variáveis e estruturando os relacionamentos.
3. **Carga (Load):** Salvamento dos dados limpos e estruturados em um banco de dados local SQLite (`dados_abertos.bd`) para permitir consultas otimizadas e análises posteriores.

## 📈 Principais Insights Gerados
* Identificação de padrões de gastos por partidos/estados
* Deputados que mais gastaram e os que menos gastaram
* Tipos de atividades/serviços que mais geram gastos
* Períodos do ano em que se tem um maior volume de gastos

## 🚀 Como executar o projeto localmente
1. Clone este repositório.
2. Certifique-se de ter o Python e o Jupyter Notebook instalados.
3. Abra e execute o notebook `Projeto_Analise_Dados_Deputados.ipynb`.
