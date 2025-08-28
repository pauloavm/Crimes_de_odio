# Análise Exploratória de Crimes de Ódio

Este projeto realiza uma análise exploratória de dados (EDA) sobre um conjunto de dados de crimes de ódio. Utilizando Python e bibliotecas como Pandas, Matplotlib e Seaborn em um ambiente Jupyter Notebook, o estudo busca identificar padrões, tendências e características principais dos incidentes reportados.

## 🎯 Objetivo da Análise

O objetivo principal é explorar o dataset `Hate_Crimes_2017-2025.csv` para extrair insights sobre a natureza dos crimes de ódio em uma localidade específica, respondendo a perguntas sobre sua evolução temporal, distribuição geográfica, motivações e tipos de ofensa.

## 📂 Arquivos no Repositório

  * `Hate_Crimes_2017-2025.csv`: O conjunto de dados brutos contendo os registros dos incidentes.
  * `analise_crimes_de_odio.ipynb`: O Jupyter Notebook com todo o código da análise, desde o carregamento e limpeza dos dados até a geração dos gráficos e modelos.
  * `Baixar_dataset.ipynb`: Notebook auxiliar para download do dataset (opcional).

## 🛠️ Ferramentas Utilizadas

  * **Linguagem:** Python 3
  * **Bibliotecas Principais:**
      * Pandas: Para manipulação e análise de dados.
      * Matplotlib e Seaborn: Para visualização de dados.
      * Statsmodels: Para modelagem de séries temporais e previsão.
  * **Ambiente:** Jupyter Notebook

## 📋 Como Executar o Projeto

1.  Clone o repositório para a sua máquina local.
2.  Certifique-se de que você tem o Python 3 e o Jupyter Notebook instalados.
3.  Instale as bibliotecas necessárias:
    ```bash
    pip install pandas matplotlib seaborn statsmodels jupyter
    ```
4.  Abra o Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
5.  Navegue até a pasta do projeto e abra o arquivo `analise_crimes_de_odio.ipynb`.
6.  Execute as células do notebook sequencialmente.

## 📊 Análises Realizadas

O notebook está estruturado para responder a uma série de perguntas, progredindo de uma análise básica para explorações mais aprofundadas.

### Análise Inicial

1.  **Tendência Temporal:** Como o número de crimes de ódio evoluiu ao longo dos anos?
      * *Ação:* Extração do ano a partir da data do incidente e plotagem de um gráfico de linhas para visualizar a tendência.
2.  **Distribuição Geográfica:** Qual a distribuição dos crimes por área administrativa (Distrito do Conselho)?
      * *Ação:* Análise da frequência de crimes por `Council District`, visualizada em um gráfico de barras.
3.  **Motivações Principais:** Quais são as motivações de preconceito (`Bias`) mais comuns?
      * *Ação:* Gráfico de barras mostrando as 10 principais motivações por trás dos incidentes.
4.  **Tipos de Ofensa:** Quais são os tipos de ofensa (`Offense(s)`) mais frequentemente reportados?
      * *Ação:* Gráfico de barras com os 10 tipos de crimes mais comuns.
5.  **Análise por Setor:** Como os crimes se distribuem pelos setores policiais (`APD Sector`)?
      * *Ação:* Gráfico de barras comparando o volume de incidentes reportados por setor.
