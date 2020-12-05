<p align="center">
  <a href="https://kaggle.com/">
    <img src="https://www.kaggle.com/static/images/site-logo.png" alt="Logo" width=72 height=72>
  </a>

  <h3 align="center">Previsão de vendas nas lojas da Rossmann</h3>

  <p align="center">
    Previsão de Vendas nas lojas da Rossmann com base em dados anteriores
    <br>
    Numpy, Pandas, Seaborn, Matplotlib, XGBoost
    <br>
    <br>
    <a href="https://github.com/AnalogicAllergy/data_science/issues/new">Reportar um bug</a>
    ·
    <a href="https://github.com/AnalogicAllergy/data_science/issues/new">Requisitar uma feature</a>
  </p>
</p>

## Índice

- [Problema](#problema)
- [Dados](#dados)
- [Etapas CRISP-DS](#etapas-crisp-ds)
- [Progresso](#progresso)
- [Dependências](#dependencias)
- [Criador](#criador)
- [Agradecimentos](#gradecimentos)
- [Copyright](#copyright)

## Problema

> Rossmann operates over 3,000 drug stores in 7 European countries. Currently, Rossmann store managers are tasked with predicting their daily sales for up to six weeks in advance. Store sales are influenced by many factors, including promotions, competition, school and state holidays, seasonality, and locality. With thousands of individual managers predicting sales based on their unique circumstances, the accuracy of results can be quite varied.

A Rossmann detém cerca de 3000 farmácias em 7 cidades da Europa. Ao gerente de cada loja foi dada a tarefa de prever as suas vendas diárias até 6 meses de antecedência. As vendas nas lojas são influenciadas por diversos fatores, dentre eles, promoções, competições, feriados escolares e estaduais, sasonalidade e localização. Com milhares de gerentes individuais predizendo vendas com base em circunstâncias únicas, a acurácia do resultado pode ser variada.

## Dados

> You are provided with historical sales data for 1,115 Rossmann stores. The task is to forecast the "Sales" column for the test set. Note that some stores in the dataset were temporarily closed for refurbishment.

Serão fornecidos dados históricos de venda de 1115 lojas da Rossmann. A tarefa é prever a columa "Vendas" no dataset de teste. Note que algumas lojas do dataset foram fechadas temporariamente para reformas

### Arquivos

Estão localizados no diretório `data`

> - train.csv - historical data including Sales
> - test.csv - historical data excluding Sales
> - sample_submission.csv - a sample submission file in the correct format
> - store.csv - supplemental information about the stores

### Campos de dados

> Most of the fields are self-explanatory. The following are descriptions for those that aren't.

> - Id - an Id that represents a (Store, Date) duple within the test set
>
> - Store - a unique Id for each store
> - Sales - the turnover for any given day (this is what you are predicting)
> - Customers - the number of customers on a given day
> - Open - an indicator for whether the store was open: 0 = closed, 1 = open
> - StateHoliday - indicates a state holiday. Normally all stores, with few > exceptions, are closed on state holidays. Note that all schools are closed on > public holidays and weekends. a = public holiday, b = Easter holiday, c = > Christmas, 0 = None
> - SchoolHoliday - indicates if the (Store, Date) was affected by the closure of > public schools
> - StoreType - differentiates between 4 different store models: a, b, c, d
> - Assortment - describes an assortment level: a = basic, b = extra, c = extended
> - CompetitionDistance - distance in meters to the nearest competitor store
> - CompetitionOpenSince[Month/Year] - gives the approximate year and month of the time the nearest competitor was opened
> - Promo - indicates whether a store is running a promo on that day
> - Promo2 - Promo2 is a continuing and consecutive promotion for some stores: 0 = store is not participating, 1 = store is participating
> - Promo2Since[Year/Week] - describes the year and calendar week when the store started participating in Promo2
> - PromoInterval - describes the consecutive intervals Promo2 is started, naming the months the promotion is started anew. E.g. "Feb,May,Aug,Nov" means each round starts in February, May, August, November of any given year for that store

## Etapas CRISP-DS

- [x] Descrição dos Dados
- [ ] Feature Engineering
- [ ] Filtragem de Variáveis
- [ ] Análise Exploratória de Dados (EDA)
- [ ] Preparação dos Dados
- [ ] Seleção de Variáveis com Algoritmo
- [ ] Modelos de Machine Learning
- [ ] Hyperparameter Fine Tuning
- [ ] Interpretação e Tradução do Erro

## Progresso

### Descrição dos Dados

    - Entendimento do Negócio do cliente
    - Definição das Etapas do CRISP-DS
    - Renomear as colunas para padrão
    - Investigação de Data Dimensions
    - Investigação de Datatypes
    - Checagem da existência de N/A
    - Corrigindo os N/A com base em conhecimento de negócio
    - Mudança dos tipos de dados após corrigir os N/A
    - Estatística Descritiva das variáveis *numéricas* (median, mean, std, skew, kurtosis)
    - Estatística Descritiva das variáveis *categóricas* (boxplot)

## Dependências

- matplotlib
- Seaborn
- Pandas
- Numpy
- Pyenv
- Inflection
- IPython

## Criador

**Willian Santana** aka _AnalogicAllergy_

## Agradecimentos

**Meigarom Fernandes**

- [GitHub](https://github.com/Meigarom)
- Canal: [Youtube](https://www.youtube.com/channel/UCar5Cr-pVz08GY_6I3RX9bA)

## Copyright

Fique a vontade para clonar, modificar e compartilhar!
