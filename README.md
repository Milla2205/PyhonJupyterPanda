# PyhonJupyterPanda
Introdução a utilização do Jupyter e o Pandas com a linguagem Python.

Lista de Exercícios - Manipulação de Dados com Pandas

Objetivo Geral
  Aprender a manipular dados de forma eficiente usando Pandas, uma das bibliotecas mais poderosas para análise de dados em Python.
  Praticar desde operações básicas (criação de Series e DataFrames) até tarefas mais complexas (filtragem, agregação e tratamento de dados).
  Preparar-se para trabalhar com dados reais, como o dataset do Titanic, que é amplamente utilizado em exercícios de ciência de dados.

Parte 1 - Conceitos Básicos

  Series:
      Crie uma Series dados com valores [10, 20, 30, 40, 50].
      Exiba índices e valores.
      Modifique índices para ['a', 'b', 'c', 'd', 'e'].

  DataFrame:
      Crie um DataFrame com colunas: Nome, Idade, Cidade.
      Adicione 5 registros fictícios.
      Exiba as primeiras 3 linhas.

  Manipulação de Índices:
      Defina Nome como índice.
      Restaure os índices padrão.

Parte 2 - Leitura e Escrita de Dados

  Leitura de CSV:
      Baixe o dataset do Titanic (link fornecido).
      Carregue o arquivo em um DataFrame.
      Exiba informações com info().

  Escrita de CSV:
      Salve o DataFrame em dados_modificados.csv.
      Confirme o salvamento carregando o arquivo novamente.

Parte 3 - Manipulação de Dados

  Seleção de Dados:
      Selecione colunas Name, Age, Sex.
      Exiba as primeiras 10 linhas.

  Filtragem:
      Filtre passageiros com idade > 30.
      Filtre mulheres que sobreviveram.

  Agregação:
      Agrupe por Pclass e calcule a média de idade.
      Conte passageiros por classe.

  Criação de Colunas:
      Crie Idade_10_anos (idade + 10).
      Crie Família (verifique SibSp > 0).


Parte 4 - Desafios Extras

   Valores Nulos:
      Identifique colunas com valores nulos.
      Substitua nulos em Age pela média das idades.

  Ordenação:
      Ordene por idade (decrescente).
      Ordene por classe e, dentro de cada classe, por idade.

  Exportação para Excel:
      Salve o DataFrame em titanic_tratado.xlsx.
