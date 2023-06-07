# XGBoost vs XGBoost Survival Embeddings

The work is devoted to the study of the applicability of Xgboost Survival Embeddings for modeling the probability of survival in a loan portfolio. The work simulates the probability of surviving using a standard approach - predicting the probability of default during the year, then using a special formula, the probability of surviving for the entire loan term is calculated. An alternative approach is to use Xgboost Survival Embeddings to predict probabilities for the entire life of the loan at once. The work perform the training of both models on the Lending club dataset and the comparison of approaches using the C-index and Kaplan-Meier curve.

- data exploration can be found in folder data_reports