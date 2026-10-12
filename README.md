# Predicción del precio de viviendas mediante modelos de regresión

Proyecto de aprendizaje automático enfocado en la predicción del precio de viviendas utilizando distintos modelos de regresión lineal. Además de evaluar el desempeño predictivo, se analiza el comportamiento de los modelos, el impacto de las técnicas de regularización y los algoritmos de optimización utilizados para entrenarlos.

---

## Objetivo

El propósito de este proyecto es estudiar el comportamiento de diferentes técnicas de regresión aplicadas al conjunto de datos **Boston Housing**, evaluando tanto su capacidad predictiva como las diferencias entre los distintos enfoques de entrenamiento.

A lo largo del análisis se desarrollan e implementan modelos de regresión lineal, algoritmos de descenso por gradiente y métodos de regularización, comparando su rendimiento mediante distintas métricas y herramientas de diagnóstico.

---

## Preguntas de investigación

Este proyecto busca responder las siguientes preguntas:

- ¿Qué variables presentan una mayor influencia sobre el precio de las viviendas?
- ¿Un modelo de regresión lineal resulta adecuado para este problema?
- ¿Qué diferencias existen entre la solución analítica y los distintos algoritmos de descenso por gradiente?
- ¿Cómo afectan las técnicas de regularización (Ridge, Lasso y Elastic Net) al rendimiento y a la selección de variables?
- ¿Qué modelo ofrece el mejor equilibrio entre capacidad predictiva e interpretabilidad?

---

## Conjunto de datos

Se utiliza el conjunto de datos **Boston Housing**, ampliamente empleado en el estudio de modelos de regresión.

El dataset contiene variables relacionadas con características demográficas, económicas y urbanísticas de distintos barrios de Boston, entre ellas:

- Tasa de criminalidad.
- Cantidad promedio de habitaciones por vivienda.
- Concentración de óxidos nítricos.
- Tasa de impuestos.
- Accesibilidad a autopistas.
- Porcentaje de población de bajo nivel socioeconómico.

La variable objetivo es el **valor medio de las viviendas**.

---

## Metodología

El desarrollo del proyecto sigue las siguientes etapas:

1. Análisis exploratorio de los datos.
2. Estudio de correlaciones entre variables.
3. Selección de características.
4. Preprocesamiento de los datos.
5. Entrenamiento de los modelos.
6. Ajuste de hiperparámetros.
7. Comparación entre modelos.
8. Diagnóstico mediante análisis de residuos.
9. Evaluación de resultados.

---

## Modelos implementados

- Regresión Lineal
- Batch Gradient Descent
- Stochastic Gradient Descent
- Mini-Batch Gradient Descent
- Ridge Regression
- Lasso Regression
- Elastic Net

---

## Evaluación

Los modelos fueron comparados utilizando:

- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)
- Coeficiente de determinación (R²)
- Validación cruzada
- Gráfico de valores reales vs. valores predichos
- Gráfico de residuos vs. valores predichos

---

## Tecnologías utilizadas

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

## Estructura del repositorio

```text
.
├── house-prices.csv
├── Prediccion_precio_viviendas.ipynb
└── README.md
```

---

## Principales resultados

- Se identificaron las variables con mayor influencia sobre el precio de las viviendas.
- La regresión lineal obtuvo un desempeño competitivo para este conjunto de datos.
- Las técnicas de regularización permitieron mejorar la estabilidad del modelo y controlar la magnitud de los coeficientes.
- Lasso realizó selección automática de variables al reducir algunos coeficientes a cero.
- Los distintos algoritmos de descenso por gradiente convergieron a soluciones comparables a la obtenida mediante la solución analítica.
- El análisis de residuos mostró un comportamiento compatible con los principales supuestos de la regresión lineal.

---

## Posibles mejoras

Como continuación de este proyecto podrían explorarse:

- Regresión Polinómica.
- Árboles de Decisión.
- Random Forest.
- Gradient Boosting.
- XGBoost.
- Ingeniería de características.
- Optimización automática de hiperparámetros.

---

## Autor

**Emmanuel Mendoza**

Estudiante de Tecnicatura en Inteligencia Artificial | Aprendizaje Automático | Ciencia de Datos
