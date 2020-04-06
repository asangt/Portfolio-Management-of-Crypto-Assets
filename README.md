# Portfolio Management of Crypto Assets (Skoltech ML project, 2020)
Team members: Aiusha Sangadiev, Andrey Poddubny, Kirill Stepanov, Kirill Bubenchikov

This repository contains the datasets and code needed to reproduce experiments from our project "Portfolio management of crypto assets".

# Setup and dependencies

+ Python
+ Numpy, pandas, scipy
+ Matplotlib
+ PyTorch

# Results
In this project, we proposed a meethod of cryptocurrency portfolio optimization using long-short term memory (LSTM) recurrent neural network coupled with temporal graph embedding ("Temporal Relational Ranking" Feng et al., 2018) to produce return forecasts for the crypto tokens. Later, these forecasts were used in mean variance portfolio (risky portfolio) optimization and Black-Litterman model to produce the portfolio weights.

![](/image/index.png)

You can see the resulting portfolios in the picture above - risk-based portfolio optimization and Black-Litterman optimization based on neural network returns outperform other methods, including the Markowitz mean variance portfolio model.
