# Projeto Python e SQLite: Gerenciamento de Banco de Dados

## Descrição

Este projeto é um *Jupyter Notebook* que demonstra o processo completo de **criação, manipulação e consulta** de um banco de dados **SQLite** utilizando a biblioteca `sqlite3` do **Python**.

O objetivo principal é fornecer um guia prático e funcional para a interação entre Python e bancos de dados relacionais leves, como o SQLite.

## Funcionalidades e Tópicos Abordados

* **Conexão e Criação de DB:** Criação de um banco de dados (`INSTRUCTOR.db`) e estabelecimento da conexão.
* **Definição de Esquema:** Criação de uma tabela (`INSTRUCTOR`) com colunas e tipos de dados definidos.
* **Operações CRUD (Create, Read, Update):**
    * Inserção de dados na tabela.
    * Consulta e recuperação de todos os dados (`SELECT *`).
    * Consulta de dados específicos (`SELECT FNAME`).
    * Atualização de registros existentes (`UPDATE`).
* **Integração com Pandas:** Demonstração de como carregar os resultados de uma consulta SQL diretamente em um *Pandas DataFrame* para análise e manipulação de dados.
* **Gerenciamento de Recursos:** Fechamento adequado da conexão com o banco de dados.

## Tecnologias Utilizadas

* Python
* SQLite3
* Pandas (para análise e visualização)
* Jupyter Notebook (`.ipynb`)
