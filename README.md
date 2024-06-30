Roadmap del Proyecto de Clasificación de Créditos
1. Descripción del Problema
Objetivo: Determinar si un cliente pertenece a una categoría de buen o mal score de crédito.
2. Preprocesamiento de Datos
Limpieza de Datos: Eliminación de datos faltantes y corrección de inconsistencias.
Normalización y Estandarización: Ajuste de variables para tener escalas comparables.
Codificación: Transformación de variables categóricas en variables numéricas.
Manejo de Valores Nulos: Imputación de valores faltantes utilizando técnicas adecuadas (media, mediana, modas, etc.).
3. Ingeniería de Características
Selección de Características: Identificación de las variables más relevantes para la predicción.
Creación de Nuevas Características: Generación de nuevas variables a partir de las existentes que podrían mejorar el rendimiento del modelo.
4. División del Conjunto de Datos
Conjunto de Entrenamiento: Usado para entrenar los modelos.
Conjunto de Prueba: Usado para evaluar el rendimiento de los modelos.
5. Entrenamiento de Modelos
a. Naive Bayes
b. LDA
c. Regresión logística
d. SVM.
e. Árboles de decisión
f. Random forest
g. Análisis de discriminante lineal
h. Análisis de discriminante cuadrático
i. AdaBoost
j. Gradient Boosting
k. XGBoost
l. LGBM

De los cuales se agregaron los mismos modelos pero con 5 hyperparametros a cada uno a los que se aplican.
6. Selección del Mejor Modelo
Random Forest:
El modelo de Random Forest fue el que mejor desempeño obtuvo en las métricas de evaluación, obteniendo 75.35% de rendimiento y prediccion acetada.
7. Validación y Ajuste del Modelo
Ajuste de Hiperparámetros: Utilización de técnicas como Grid Search o Random Search para encontrar la mejor configuración de hiperparámetros del modelo de Random Forest.
