# Predicción del Índice de Comercio Minorista (INE)

Proyecto de análisis y modelización de series temporales aplicado al  
**Índice de Comercio al por menor sin estaciones de servicio (INE, España)**.

El objetivo del presente proyecto es modelar la evolución histórica del índice y generar
predicciones robustas con un enfoque principal en la toma de decisiones empresariales.

Objetivos adicionales del Proyecto

- Analizar la estructura temporal del índice en cuanto a tendencia y estacionalidad.
- Comparar distintos métodos de predicción.
- Validar modelos mediante estimación de MAE y RMSE.
- Generar predicciones con intervalos de confianza.
- Extraer conclusiones estratégicas aplicables a empresas del sector minorista.

Metodología

Análisis Exploratorio
- Visualización de la serie
- Descomposición en tendencia, estacionalidad y residuo
- Identificación de eventos atípicos como crisis económicas y pandemia

Métodos de Suavizado Exponencial

Se probaron los siguientes modelos:

- Suavizado Exponencial Simple (SES)
- Holt (tendencia)
- Holt-Winters Aditivo
- Holt-Winters Multiplicativo

Modelización SARIMA
- Análisis ACF y PACF
- Diferenciación regular y estacional
- Ajuste del modelo SARIMA
- Diagnóstico de residuos

Predicciones

- Horizonte: 12 meses
- Generación de intervalos de confianza
- Interpretación estratégica


Algunos Resultados Clave

- El modelo Holt-Winters Aditivo presentó el mejor desempeño en el contexto del dataset.
- El modelo SARIMA capturó adecuadamente la dependencia temporal y estacional.
- La serie presenta estacionalidad anual estructural.
- Los intervalos de confianza permiten simular escenarios optimista y conservador.


Tecnologías Utilizadas

- Python
- Pandas
- NumPy
- Statsmodels
- Scikit-learn
- Matplotlib
- Jupyter Notebook


