# Profolio
Project Overview
This repository contains the most recent time series prediction competition code and post-competition neural network implementations. The training code for the 2022 competition has unfortunately been lost. Hence, provided here are the final submission code for a recent time series forecasting contest and neural network applications replicated post-competition. Notably, the neural network code is a replication of an open-source project, applied here for educational purposes on real stock data.

File Descriptions
tuned-lightgbm-best-public-score.ipynb and 新的线下测试集.ipynb: These notebooks include my competition submission and offline validation scripts, respectively. The submission script details the ensemble logic and the features selected for the final model. The offline validation script elaborates on the testing logic, using segmented, non-leaking time series 5-fold cross-validation to ensure integrity in the testing process.
jointquant_lstminfer.ipynb and jointquantnengyongdedaima.ipynb: These files pertain to LSTM and 1DCNN models and cover several critical steps in time series neural network processing. Steps include: 1) Normalizing data, 2) Organizing data into mini-batches according to the sequence of the time series (ensuring no data leakage and allowing the model to learn temporal information), and 3) Feeding the time-series data into the model for training.
Source of Model Structures
The NN model structures are adapted from a source available on GitHub, which can be accessed [here](https://github.com/nimashahbazi/optiver-trading-close).
