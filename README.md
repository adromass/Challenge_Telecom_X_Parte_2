# Telecom X – Predicción de Cancelación de Clientes (Churn)

## Introducción

En este proyecto se desarrolló un análisis predictivo para identificar clientes con mayor probabilidad de cancelar sus servicios en **Telecom X**. La tarea consistió en preparar los datos, entrenar modelos de clasificación y analizar los factores más relevantes que influyen en la cancelación, con el objetivo de generar insights estratégicos que permitan a la empresa implementar acciones de retención.

El trabajo incluyó las siguientes etapas principales:

1. **Preprocesamiento de datos:** se codificaron variables categóricas, se normalizaron variables numéricas y se aplicó **SMOTE** para balancear la clase de cancelación, asegurando que los modelos tuvieran datos representativos de ambas clases.  
2. **Análisis de correlación y selección de variables:** se identificaron relaciones entre las variables y se eliminaron problemas de multicolinealidad, destacando las más relevantes para la predicción.  
3. **Entrenamiento de modelos de clasificación:** se utilizaron **Regresión Logística** y **Random Forest** para predecir la probabilidad de cancelación de los clientes.  
4. **Evaluación de modelos:** se calcularon métricas como exactitud, precisión, sensibilidad y F1-score, además de analizar las matrices de confusión para comprender el desempeño de cada modelo.  
5. **Interpretación de resultados:** se analizaron los coeficientes de la Regresión Logística y la importancia de variables en Random Forest para identificar los factores críticos que afectan la cancelación de clientes.  

Los principales hallazgos indican que variables como **cargo mensual**, **cuentas diarias**, **cargo total** y **antigüedad en meses** son determinantes para predecir la cancelación. Asimismo, factores contractuales y servicios adicionales contribuyen a la retención. Este análisis proporciona una base sólida para que Telecom X implemente estrategias de prevención y fidelización de clientes.

### Adrian Massella
