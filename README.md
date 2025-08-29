## Plan de trabajo

1. EDA de cada dataset (mirar faltantes, outliers, distribuciones, correlaciones, estacionalidad en series).
2. Definir prompts de trabajo → un prompt por punto (para abrir en chats separados y que cada uno tenga contexto).
3. Investigación de modelos apropiados para cada caso:

- Punto 1: regresión tabular (RF, XGBoost, Regresión Lineal, etc.).
- Punto 2: clustering funcional (curvas → FPCA + k-means, o scikit-fda).
- Punto 3: forecasting (AutoARIMA, Prophet, posiblemente LSTM si da tiempo).
4. Construcción de modelos y validación (MAPE/R² según aplique).
5. Generación de outputs para Sheets (tablas + gráficas + explicaciones).
6. Montaje del entregable en Google Sheets.