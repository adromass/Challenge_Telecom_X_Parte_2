# Telecom X – Predicción de Cancelación de Clientes (Churn)

## Introducción

Este proyecto tuvo como objetivo desarrollar un modelo predictivo para identificar clientes con mayor probabilidad de cancelar sus servicios en **Telecom X**. El análisis incluyó preprocesamiento de datos, entrenamiento de modelos de clasificación, evaluación de métricas clave y extracción de insights estratégicos para guiar acciones de retención.

Se trabajó con variables categóricas codificadas, normalización de variables numéricas y balanceo de clases mediante **SMOTE**. Para la predicción se entrenaron modelos de **Regresión Logística** y **Random Forest**, evaluando su desempeño con métricas como exactitud, precisión, sensibilidad y F1-score, y analizando la importancia de las variables para interpretar los resultados.

Los hallazgos más relevantes muestran que los **cargos mensuales y totales**, las **cuentas diarias** y la **antigüedad del cliente** son los factores más determinantes para la cancelación. Además, el **tipo de contrato**, los **servicios adicionales** y el **método de pago** influyen en la retención. Estos resultados permiten priorizar estrategias de fidelización y personalización de planes para minimizar la pérdida de clientes.

## Librerías y herramientas utilizadas

El proyecto se implementó utilizando librerías de análisis de datos, visualización y Machine Learning, incluyendo: `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly.express`, `MinMaxScaler` para normalización, `SMOTE` para balance de clases, `train_test_split` para partición de datos, `variance_inflation_factor` para multicolinealidad, modelos de sklearn como `DummyClassifier`, `DecisionTreeClassifier` y métricas de evaluación como `accuracy_score`, `precision_score`, `recall_score`, `f1_score` y curvas ROC.

Este enfoque permitió construir un pipeline robusto, interpretativo y orientado a la toma de decisiones estratégicas de la empresa.


### Adrian Massella
