# TFM_ML_Interpretable

En este repositorio se alojan los métodos y técnicas de explicabilidad utilizadas para realizar la comparativa de modelos de Machine Learning interpretables, en la tarea predicción de riesgo creditirio, sobre el conjunto de datos de crédito con garantía hipotecaria (HELOC) [1] como parte del Trabajo de Fin de Máster en Inteligencia Artificial (UNIR, 2020-2021)

El trabajo se ha realizado en Python y sigue la siguiente estructura:

1.	Procesamiento de datos
2.	Arquitectura de los modelos
3.	Interpretabilidad de los modelos
4.	Métricas de interpretabilidad


El archivo [creditRiskInterpretability.ipynb](https://github.com/sortegamart/TFM_ML_Interpretable/blob/main/creditRiskInterpretability.ipynb) contiene el código fuente.

Se indica a continuación la información almacenada en las distintas carpetas:  
/instances - Figuras de ejemplos de interpretación una instancia utilizando las técnicas de LIME y SHAP aplicadas a los modelos de Red Neuronal (CNN) y XGBoost.  
/metrics   - Ficheros csv con la información de valores LIME y SHAP aplicado a CNN y XGBoost para 1000 muestras y resultados de las métricas de interpretabilidad.  
/models    - Modelos entrenados.  




[1] FICO community. (2018). Explainable Machine Learning Challenge. https://community.fico.com/s/explainable-machine-learning-challenge Último acceso: 19/07/2021
