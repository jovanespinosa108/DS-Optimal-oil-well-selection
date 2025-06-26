🛢️ Proyecto 11: Selección Óptima de Pozos Petroleros (OilyGiant)

💼 Machine Learning Aplicado a Negocios

Author: Jovan Espinosa
Fecha: Junio 2025

📌 Descripción del Proyecto | Project Description

ES:
Trabajas para la compañía petrolera ficticia OilyGiant. Tu tarea es identificar las mejores ubicaciones para desarrollar 200 nuevos pozos petroleros, utilizando datos geológicos y modelos de aprendizaje automático.

El proyecto consiste en:

Analizar datos de 3 regiones.

Entrenar un modelo de regresión lineal para predecir el volumen de reservas.

Seleccionar los 200 pozos con mayores predicciones.

Calcular ganancias potenciales y riesgos.

Aplicar bootstrapping para evaluar incertidumbre.

Elegir la región óptima con mayor rentabilidad y riesgo menor al 2.5%.

EN:
You are working for the fictional oil extraction company OilyGiant. Your task is to identify the best drilling locations for 200 new oil wells using geological data and machine learning models.

This project includes:

Analyzing data from 3 regions.

Training a linear regression model to predict oil reserves.

Selecting the top 200 predicted wells.

Calculating potential profits and risk.

Applying bootstrapping to evaluate uncertainty.

Choosing the optimal region with highest return and less than 2.5% risk of loss.

📂 Estructura del Proyecto | Project Structure

project_11_oilygiant/
├── data/
│   ├── geo_data_0.csv
│   ├── geo_data_1.csv
│   └── geo_data_2.csv
├── oilygiant_oil_wells.ipynb        # Notebook principal del análisis
├── README.md

🧠 Herramientas y Tecnologías | Tools & Technologies

Python 3

pandas, numpy, matplotlib, seaborn

scikit-learn (LinearRegression, metrics)

Bootstraping (via np.random and statistical analysis)

Jupyter Notebook

🚀 Objetivos | Objectives
ES:

Predecir volumen de reservas (en miles de barriles).

Evaluar potencial económico según presupuesto ($100M).

Identificar riesgos financieros.

Automatizar la selección de pozos rentables.

EN:

Predict oil reserve volumes (in thousands of barrels).

Evaluate economic potential under a $100M budget.

Identify financial risks.

Automate profitable well selection.

✅ Resultados Esperados | Expected Outcomes
ES:

Selección de la mejor región con base en ganancia promedio y riesgo de pérdida.

Evaluación de desempeño del modelo (RMSE, comparación con media real).

Reporte de intervalo de confianza y distribución de ganancias (bootstrapping).

EN:

Select the best region based on average profit and risk of loss.

Model performance evaluation (RMSE, comparison to actual mean).

Profit confidence interval and distribution report (via bootstrapping).

📈 Evaluación de Riesgo | Risk Evaluation
Se usa bootstrapping con 1000 repeticiones para simular múltiples escenarios.

Se calcula el intervalo de confianza del 95%.

El riesgo se define como la probabilidad de pérdida financiera (ganancia negativa).

💬 Conclusión | Conclusion

ES:
Este proyecto demuestra la aplicación de modelos de regresión lineal y análisis estadístico para la toma de decisiones de alto impacto financiero. Se sigue una estructura de negocio con evaluación de riesgo y retorno, permitiendo recomendar la región óptima para desarrollar pozos.

EN:
This project shows how linear regression and statistical analysis can be applied to high-stakes business decisions. It follows a business-driven structure with risk and return evaluation, leading to a well-justified recommendation for the most profitable drilling region.

