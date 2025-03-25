# Análise de Dados: Anomalias de Temperatura Global

Este projeto realiza uma análise exploratória de dados sobre as anomalias de temperatura global ao longo dos anos. O objetivo é identificar tendências, picos de anomalias e possíveis evidências de aquecimento global. O conjunto de dados utilizado contém informações sobre a temperatura média anual e suas variações em relação a uma média histórica.

---

## 📊 Dados Utilizados

Os dados foram obtidos a partir do **NASA Goddard Institute for Space Studies (GISS)**
*NASA Goddard Institute for Space Studies (GISS). (n.d.). GISS Surface Temperature Analysis (GISTEMP). Retrieved March 12, 2025, from https://data.giss.nasa.gov/gistemp/*

---

## 🛠️ Ferramentas e Bibliotecas

- **Python**: Linguagem de programação utilizada.
- **Pandas**: Para manipulação e análise dos dados.
- **Seaborn e Matplotlib**: Para visualização dos dados.
- **Jupyter Notebook**: Ambiente de desenvolvimento interativo.

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
