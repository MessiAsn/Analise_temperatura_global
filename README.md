# Análise de Dados: Anomalias de Temperatura Global

Este projeto realiza uma análise exploratória de dados sobre as anomalias de temperatura global ao longo dos anos. O objetivo é identificar tendências, picos de anomalias e possíveis evidências de aquecimento global. O conjunto de dados utilizado contém informações sobre a temperatura média anual e suas variações em relação a uma média histórica.

---

## 📁 Estrutura do Projeto

- **`temperatura_global_anual.csv`**: Arquivo CSV contendo os dados de anomalias de temperatura global.
- **`analise_temperatura.ipynb`**: Notebook Jupyter com o código completo da análise.
- **`README.md`**: Este arquivo, com informações sobre o projeto.

---

## 📊 Dados Utilizados

Os dados foram obtidos a partir do **NASA Goddard Institute for Space Studies (GISS)** e contêm as seguintes colunas:

- **Year**: Ano da medição.
- **Mean**: Anomalia média da temperatura global em relação a uma média histórica.
- **Source**: Fonte dos dados (ex.: GISTEMP, gcag).

---

## 🛠️ Ferramentas e Bibliotecas

- **Python**: Linguagem de programação utilizada.
- **Pandas**: Para manipulação e análise dos dados.
- **Seaborn e Matplotlib**: Para visualização dos dados.
- **Jupyter Notebook/Google Colab**: Ambiente de desenvolvimento interativo.

---

## 📈 Análises Realizada

### 1. **Exploração dos Dados**
   - Descrição estatística da coluna `Mean` (anomalias de temperatura).
   - Identificação de valores mínimos, máximos, média e desvio padrão.

### 2. **Visualização da Distribuição**
   - Histograma com curva de densidade (KDE) para verificar a distribuição das anomalias.
   - Identificação de uma assimetria à direita, indicando anos mais quentes recentes.

### 3. **Identificação de Picos de Anomalia**
   - Listagem dos 10 anos com as maiores anomalias de temperatura.
   - Gráfico de dispersão mostrando a evolução das anomalias ao longo dos anos.
   - Gráfico de barras horizontal destacando os anos com maiores anomalias.

### 4. **Análise por Década**
   - Cálculo da média das anomalias por década.
   - Gráfico de barras mostrando a tendência de aumento das anomalias ao longo das décadas.

## 📌 Sugestões para Análises Futuras

### 1. **Correlação com Fenômenos Climáticos**
   - Investigar a relação entre anomalias de temperatura e fenômenos como **El Niño** e **La Niña**.

### 2. **Modelagem Preditiva**
   - Utilizar modelos de aprendizado de máquina para prever anomalias futuras com base em dados históricos.

### 3. **Análise Regional**
   - Se disponíveis, analisar dados regionais para entender como as anomalias variam em diferentes partes do mundo.
