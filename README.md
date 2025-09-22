# Análise do PIB de Brasil, EUA e China 📊
Este projeto realiza a análise do Produto Interno Bruto (PIB) dos países Brasil, Estados Unidos e China ao longo dos anos, com visualizações de dados, identificação de tendências e previsões utilizando o modelo ARIMA.

# 📋 Objetivo
O principal objetivo é explorar os dados de PIB desses três países, identificar padrões de crescimento econômico e prever valores futuros com base em séries temporais.

# 🚀 Funcionalidades
- Coleta de dados históricos do PIB dos países Brasil, EUA e China utilizando a biblioteca wbdata.
- Visualização do crescimento do PIB ao longo dos anos.
- Análise das tendências econômicas de cada país.
- Previsão de PIB com o modelo ARIMA para identificar possíveis cenários futuros.
- Exportação dos dados para arquivo CSV.

# 🛠️ Tecnologias Utilizadas
- Python
- Pandas: Manipulação e análise de dados.
- Matplotlib: Visualização de gráficos.
- Statsmodels: Análise de tendências em séries temporais.
- Pmdarima: Implementação do modelo ARIMA.
- Wbdata: Obtenção de dados econômicos da API do Banco Mundial.

# 📈 Fluxo do Projeto
Coleta de Dados: Os dados são obtidos pela API do Banco Mundial para os anos de 2000 a 2025.

Análise Exploratória: São criados gráficos para visualizar a evolução do PIB de cada país.

Análise de Tendências: A decomposição da série temporal permite observar tendências econômicas.

Previsão: Usamos o modelo ARIMA para prever o PIB com base nos dados históricos.
