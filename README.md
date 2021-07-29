# Proyecto 1 - Seminario de Inteligencia Artificial

### Kaggle Competition - House Prices - Advanced Regression Techniques

Una regresión lineal simple para el proyecto de precios de casas. 

- Tenemos > 70 variables explicativas. 
- **Objetivo:** Dar el precio de la casa en cuestión.

[Link a Kaggle](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)

#Puntuación 

![2021-07-29 17.48.00 www.kaggle.com 6bf6bf4b5451.png](data:image/png;base64,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)
