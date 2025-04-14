# LLAMA3.2_2_XOM_prediction
Utilizing LLAMA 3.2 to make 5 minutes price predictions for XOM

+ Parse news using Refinitiv Workspace
+ Convert them to embeddings using LLAMA 3.2 (ollama proxy)
+ Use PCA to cut dimensionality
+ Train CatBoost Model on XOM (ExxonMobil) stock returns on 5 minute range using embeddings above as features
+ Plot possible returns ob backtest
