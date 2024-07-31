### README (Português)

# Análise de Dados de COVID-19

Este projeto realiza uma análise detalhada dos dados de casos confirmados de COVID-19, utilizando várias bibliotecas de Python para manipulação de dados, visualização e análise geográfica. O objetivo é entender a distribuição geográfica e a evolução dos casos ao longo do tempo.

## Estrutura do Projeto

1. **Carga e Limpeza de Dados**: 
   - Carregamento do conjunto de dados.
   - Remoção de valores nulos e tratamento de dados inconsistentes.

2. **Análise Geográfica**:
   - Agrupamento dos dados por país e soma dos casos confirmados.
   - Criação de um mapa de calor utilizando a biblioteca Folium para visualizar a distribuição geográfica dos casos.
   - O mapa de calor é salvo em um arquivo HTML para fácil visualização.

3. **Análise de Crescimento Diário**:
   - Agrupamento dos dados por país/região e soma dos casos confirmados.
   - Cálculo da taxa de crescimento diário dos casos confirmados para países selecionados.
   - Visualização da taxa de crescimento diário utilizando gráficos de linhas.

4. **Análise de Aumento de Casos**:
   - Cálculo do aumento diário dos casos confirmados.
   - Visualização do aumento de casos ao longo do tempo para países selecionados.

## Bibliotecas Utilizadas

- pandas
- matplotlib
- seaborn
- folium

## Executando o Projeto

1. Certifique-se de ter todas as bibliotecas necessárias instaladas:
   ```bash
   pip install pandas matplotlib seaborn folium
   ```

2. Execute o script Python para gerar as análises e visualizações:
   ```bash
   python analise_covid19.py
   ```

3. Abra o arquivo `covid19_heatmap.html` para visualizar o mapa de calor.

## Resultados

- Mapas de calor que mostram a distribuição geográfica dos casos de COVID-19.
- Gráficos de linha que ilustram a taxa de crescimento diário dos casos em diversos países.
- Gráficos de linha que mostram o aumento diário dos casos confirmados.

---

### README (English)

# COVID-19 Data Analysis

This project conducts a detailed analysis of confirmed COVID-19 case data using various Python libraries for data manipulation, visualization, and geographic analysis. The goal is to understand the geographical distribution and the evolution of cases over time.

## Project Structure

1. **Data Loading and Cleaning**:
   - Loading the dataset.
   - Removing null values and handling inconsistent data.

2. **Geographical Analysis**:
   - Grouping data by country and summing confirmed cases.
   - Creating a heat map using the Folium library to visualize the geographical distribution of cases.
   - The heat map is saved as an HTML file for easy viewing.

3. **Daily Growth Analysis**:
   - Grouping data by country/region and summing confirmed cases.
   - Calculating the daily growth rate of confirmed cases for selected countries.
   - Visualizing the daily growth rate using line charts.

4. **Case Increase Analysis**:
   - Calculating the daily increase in confirmed cases.
   - Visualizing the increase in cases over time for selected countries.

## Libraries Used

- pandas
- matplotlib
- seaborn
- folium

## Running the Project

1. Ensure all necessary libraries are installed:
   ```bash
   pip install pandas matplotlib seaborn folium
   ```

2. Run the Python script to generate the analyses and visualizations:
   ```bash
   python covid19_analysis.py
   ```

3. Open the `covid19_heatmap.html` file to view the heat map.

## Results

- Heat maps showing the geographical distribution of COVID-19 cases.
- Line charts illustrating the daily growth rate of cases in various countries.
- Line charts showing the daily increase of confirmed cases.
