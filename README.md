# Project_1_Demand_Forecasting
This repository provides models for demand forecasting using machine learning techniques. It is designed to help manufacturing companies optimize inventory levels, reduce waste, and improve production planning. By predicting future demand more reliably, businesses can enhance operational efficiency and respond proactively to market changes.

## Notebook's structure
The notebook is made of the following sections:
- Loading the data: the dataset is taken, to perform the models
- Explorative Data Analysis (EDA): it is performed to better understand the structure and characteristics of the dataset, and the nature of the variables
- Preprocessing: the features of the dataset are modified to try to gain as much information as possible from them, without implementing models yet
- Model: this section is divided in 3 different implementations, a Random Forest baseline verison, a Random Forest with hyperparameter tuning and XGBoost
- Comparison between models' performances: the outputs of the models are extracted in order to understand which one is the best

## Business insights for manufacturing companies
Implementing machine learning models for sales demand forecasting offers valuable business insights that can support strategic decision-making. Accurate demand predictions enable manufacturers and retailers to optimize inventory levels, reducing both stockouts and excess inventory costs. This leads to improved cash flow management and lower warehousing expenses. Additionally, understanding demand patterns allows businesses to better plan promotions, pricing strategies, and supply chain logistics. Machine learning models can uncover complex, non-linear relationships in the data—such as the impact of promotions, seasonality, and regional trends—that traditional forecasting methods might overlook.

## Results
The performance of three different models was evaluated using R² Score, RMSE, and MAE metrics. The XGBoost model outperformed both the base and optimized Random Forest models, achieving the highest R² score (0.81) and the lowest RMSE (18.75) and MAE (12.02). The base Random Forest provided competitive results with good balance between correctness and model simplicity. These results confirm the robustness of XGBoost for demand forecasting tasks.
In practice, this means the model can reliably predict sales demand, reducing the risk of stockouts and overstocking. With an average absolute error of just 12 units, businesses can make more informed decisions about inventory planning, production scheduling, and distribution, resulting in cost savings, improved customer satisfaction, and more efficient resource allocation.
