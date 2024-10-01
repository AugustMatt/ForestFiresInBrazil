# Queimadas Florestais no Brasil

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-1.x-orange.svg)
![Seaborn](https://img.shields.io/badge/Seaborn-0.x-green.svg)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.x-red.svg)

## Visão Geral

Este projeto realiza uma análise dos dados de queimadas florestais no Brasil ao longo de aproximadamente 10 anos. O conjunto de dados utilizado foi obtido do [Kaggle: Queimadas Florestais no Brasil](https://www.kaggle.com/datasets/gustavomodelli/forest-fires-in-brazil). O principal objetivo é entender tendências, identificar padrões e visualizar a extensão das queimadas em diversos estados do Brasil.

## Conjunto de Dados

O conjunto de dados contém informações sobre as queimadas florestais, organizadas por ano, estado e número de queimadas detectadas. As principais colunas do dataset são:
- **year**: O ano em que as queimadas foram registradas.
- **state**: O estado no Brasil onde ocorreu a queimada.
- **month**: O mês em que ocorreu o evento de queimada.
- **number**: O número de queimadas reportadas.

## Definição do Problema

O objetivo é responder às seguintes perguntas-chave:
1. Quais estados são mais afetados pelas queimadas?
2. Como o número de queimadas mudou ao longo dos anos?
3. Quais são os meses com o maior número de queimadas?
4. Existem tendências perceptíveis em regiões específicas do Brasil?

## Etapas

1. **Carregamento e Inspeção dos Dados**:
   - Carregar o conjunto de dados usando o `pandas`.
   - Inspecionar a estrutura dos dados (tipos, valores faltantes, etc.).
   
2. **Limpeza dos Dados**:
   - Tratar valores ausentes e inconsistências nos dados.
   - Garantir que os dados estejam no formato correto para análise.

3. **Análise Exploratória de Dados (EDA)**:
   - Visualizar a distribuição das queimadas por diferentes estados e anos.
   - Identificar tendências no número de queimadas ao longo do tempo.
   - Analisar os meses com maior ocorrência de queimadas.

4. **Resultados**:
   - Gerar insights a partir das visualizações e estatísticas descritivas.
   - Responder às principais perguntas sobre as tendências das queimadas no Brasil.

## Requisitos

Para rodar este projeto localmente, você precisará das seguintes bibliotecas Python:

```bash
  pip install pandas seaborn matplotlib
```

- pandas: Para manipulação e análise de dados.
- seaborn: Para criar visualizações bonitas.
- matplotlib: Para plotar gráficos e diagramas.

## Como Executar
- Clone este repositório para sua máquina local:
```bash
  git clone https://github.com/AugustMatt/ForestFiresInBrazil.git
  cd ForestFiresInBrazil
```
- Instale as bibliotecas necessárias usando pip:
```bash
  pip install -r requirements.txt
```
- Execute a análise utilizando o notebook Jupyter fornecido ou scripts Python.
