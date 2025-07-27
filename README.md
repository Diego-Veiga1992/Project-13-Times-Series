📈 Time Series Forecasting - Taxi Orders
📝 Projeto
Este projeto utiliza dados históricos de pedidos de táxi para prever a quantidade de corridas na próxima hora. A previsão ajuda a empresa Sweet Lift Taxi a atrair mais motoristas durante horários de pico.

O modelo final deve alcançar um erro quadrático médio raiz (RMSE) inferior a 48 na amostra de teste.

📂 Estrutura do Projeto
Resample dos dados: os dados foram ajustados para intervalos de uma hora.

Análise exploratória: visualizações e decomposição de série temporal.

Modelagem: testes com diferentes modelos e hiperparâmetros.

Avaliação: divisão dos dados com 10% para teste e análise final do desempenho dos modelos.

📊 Dados
O dataset está armazenado no arquivo taxi.csv e possui a seguinte coluna principal:

num_orders – número de pedidos de táxi por hora.

🧠 Modelos Utilizados
Random Forest

Linear Regression

LightGBM

Lasso Regression

CatBoost

XGBoost

🧪 Avaliação
A métrica utilizada para avaliar o desempenho dos modelos é:

RMSE (Root Mean Squared Error)

✅ Resultados
O melhor modelo obteve RMSE abaixo de 48, conforme exigido pelo projeto.

🛠 Tecnologias e Bibliotecas
Python

Pandas, NumPy

Scikit-learn

Matplotlib

Statsmodels

LightGBM, CatBoost, XGBoost

📁 Como Executar
Clone o repositório.

Certifique-se de ter o Python 3.8+ instalado.

Instale as dependências:

bash
Copiar
Editar
pip install -r requirements.txt
Execute o notebook:

bash
Copiar
Editar
jupyter notebook "project 13 Time Series.ipynb"
📌 Observações
Os dados devem estar no mesmo diretório do notebook ou o caminho deve ser ajustado.

Reproduzir os resultados pode variar dependendo do ambiente e versão das bibliotecas.

Se quiser, posso gerar também um requirements.txt com base nas bibliotecas usadas no notebook. Deseja isso? 








Você disse:
em inglês 


O ChatGPT disse:
Sure! Here's the README.md translated into English:

📈 Time Series Forecasting - Taxi Orders
📝 Project Overview
This project leverages historical taxi order data to predict the number of orders for the upcoming hour. The goal is to help Sweet Lift Taxi attract more drivers during peak times by accurately forecasting demand.

The final model must achieve a Root Mean Squared Error (RMSE) below 48 on the test set.

📂 Project Structure
Resampling: The original data is resampled into hourly intervals.

Exploratory Analysis: Includes visualizations and time series decomposition.

Modeling: Multiple models with different hyperparameters are trained.

Evaluation: The dataset is split, with 10% used as a test set, and models are evaluated accordingly.

📊 Dataset
The dataset is stored in a file called taxi.csv and contains the following key column:

num_orders – the number of taxi orders per hour.

🧠 Models Used
Random Forest

Linear Regression

LightGBM

Lasso Regression

CatBoost

XGBoost

🧪 Evaluation Metric
The primary metric used to evaluate model performance is:

RMSE (Root Mean Squared Error)

✅ Results
The best-performing model achieved an RMSE below 48, meeting the project’s success criterion.

🛠 Technologies and Libraries
Python

pandas, numpy

scikit-learn

matplotlib

statsmodels

lightgbm, catboost, xgboost

📁 How to Run
Clone this repository.

Ensure Python 3.8+ is installed.

Install dependencies:

bash
Copiar
Editar
pip install -r requirements.txt
Open the notebook:

bash
Copiar
Editar
jupyter notebook "project 13 Time Series.ipynb"
📌 Notes
Make sure the taxi.csv dataset is in the same directory as the notebook, or adjust the file path accordingly.

Results may vary slightly depending on your environment and package versions.
