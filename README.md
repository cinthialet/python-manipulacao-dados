# Manipulação de Dados com Python

## Objetivo
Este repositório é um reflexo da minha jornada para desenvolver habilidades robustas de manipulação de dados utilizando Python. O projeto é estruturado em torno de demandas reais da área de negócios, replicando cenários encontrados no mundo corporativo, com o objetivo de demonstrar a eficácia das ferramentas e técnicas em contextos práticos. Espera-se que, ao se deparar com essas demandas, o leitor perceba a versatilidade do Python e sua potência em análise de dados.

## Demandas da Área de Negócio
Estas demandas foram estrategicamente escolhidas para simular situações reais em que a manipulação de dados é crucial para a extração de insights. Elas servem como um guia progressivo, aumentando em complexidade, para aprimorar e demonstrar diferentes facetas das habilidades em Python para manipulação de dados.
- Demanda 1 : No df2, criar uma coluna que seja um identificador único de cada registro da tabela
- Demanda 2 : Criar coluna com 'PREÇO MÉDIO REVENDA' convertido em dólares, considerando taxa cambial de 1:5
- Demanda 3 : Mostrar todos os estados cujos os preços dos combustíveis foram aferidos
- Demanda 4 : Quantos registros há no dataset por estado?
- Demanda 5 : Selecionar os preços dos Postos de São Paulo
- Demanda 6 : Selecionar os preços dos Postos de São Paulo, Rio de Janeiro e Maranhao
- Demanda 7 : Selecionar: registros de postos do Rio de Janeiro com Preços Médio de Revenda acima de **2 reais**
- Demanda 8 : Selecionar os registros de postos do Rio de Janeiro **OU** com Preços Médio de Revenda acima de 2 reais
- Demanda 9 : Selecionar os registros de postos do Rio de Janeiro **OU** do Maranhão com Preços Médio de Revenda entre 1 e 2 reais (incluso)
- Demanda 10 : Selecionar os registros de postos de São Paulo ou do Rio de Janeiro com Gasolina Comum acima de 2 reais**
- Demanda 11 : Achar a data referente às últimas 2 semanas , considerando que a data atual sempre mudará a cada dia diferente de processamento.
- Demanda 12 : Criar uma coluna com os os dias que se passaram entre a data final e a data inicial
- Demanda 13 : Corrigir todos os dados numéricos que estão com tipagem object, para o correto
- Demanda 14 : Preencher os valores numéricos nulos por zero
- Demanda 15 : Identificar os registros preenchidos com zero nas colunas seleciondas da demanda anterior e excluí-las do dataset
- Demanda 16 : Enviar o resultado como um arquivo para a área de negócio - csv e xlsx
- Demanda 17 : Identificar o maior preço médio de revenda para cada região
- Demanda 18 : Identificar o menor preço médio de revenda por região e por data final
- Demanda 19 : Demonstrar o min e max do 'PREÇO MÉDIO REVENDA' para cada região
- Demanda 20 : Criar um ranking das regiões com maior preço médio de revenda.
- Demanda 21 : Para as análises futuras, a área de negócio precisa de dados que contemples apenas anos cheios (Jan-Dez). Exclua os anos que não corresponderem a esse critério
- Demanda 22 : Qual a proporção de postos pesquisados para cada tipo de combustível, em cada região ?
- Demanda 23 : Como os preços da Gasolina Comum em São Paulo variaram em 2018?
- Demanda 24 : Como os preços da Gasolina Comum e do Etanol em São Paulo variaram em 2018?

## Pacotes Utilizados
- **Pandas:** Biblioteca primária para manipulação de dados tabulares.
- **Numpy:** Usado para operações numéricas avançadas e tratamento de arrays.
- **Datetime:** Facilita a manipulação e formatação de datas.

## Sobre os Dados
- **Dataset:** [Gas Prices in Brazil](https://www.kaggle.com/matheusfreitag/gas-prices-in-brazil)
- **Descrição:** O conjunto de dados reflete os preços médios semanais dos combustíveis no Brasil de 2004 a 2019. Entre os atributos mais relevantes estão: 'ESTADO', 'PRODUTO', 'NÚMERO DE POSTOS PESQUISADOS' e 'PREÇO MÉDIO REVENDA'.

## Estrutura do Projeto
- **Notebook:** `manipulacao_dados_python.ipynb`
- 
- **output:** Arquivos gerados durante o notebook. Exemplos incluem:
  - `dados_pre_processados.csv`
  - `dados_pre_processados.xlsx`
  - `dados_resultantes_com_index.csv`
  - `dados_resultantes_sem_index.csv`
  - `df_variacao_combustiveis_sp_2018.csv`
  - `resultado_agrupamento_regiao_datafin.csv`
  - `resultado_agrupamento_regiao_datafin.xlsx`
  
- **dados:** O dataset base do projeto: `GasPricesinBrazil_2004-2019.csv`

