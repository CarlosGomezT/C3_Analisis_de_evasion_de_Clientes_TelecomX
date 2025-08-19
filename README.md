
---

# 📊 **Análisis con Machine Learning para detectar el abandono en Telecom X**

---

## :boom: Introducción

---

El siguiente análisis forma parte de un estudio ficticio por parte de mi formación como estudiante de Oracle Next Education, siendo el segundo desafío por completar para mi desarrollo como analista de datos (Data Science). 

Tras un previo análisis realizado para la empresa Telecom X, se identificaron las principales causas por las cuales los clientes de la empresa estaban cancelando su servicio, utilizando herramientas de manipulación de datos y observando estadísticas pudimos inferir situaciones por las cuales los clientes estaban abandonando.

Ahora nuestro trabajo consiste en crear modelos de Machine Learning con los cuales seamos capaces de detectar posibles abandonos a futuro.  Con la creación de modelos y el análisis de nuestra base de datos, se desarrollaron conclusiones para evitar el futuro abandono de los clientes, desarrollando estrategias para reducir la taza de abandonos e identificar a los clientes que son propensos a abandonar.


Puede acceder al codigo descargando el archivo .ipynb en el repositorio o entrando al siguiente link de google collab

<a target="_blank" href="https://colab.research.google.com/drive/1A5V4XlIvjHKATS1KnVc7q1UDQsPzNyxI?usp=sharing">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

---

## 📌 **Descripción General**

---


Este proyecto es parte de un análisis realizado por y para Telecom X donde se desarrollan modelos de aprendizaje que buscan identificar las tendencias de los clientes que son orillados a cancelar sus servicios.  Con el objetivo de reducir la cantidad de clientes que abandonan y entenderemos el comportamiento de los clientes dentro de la empresa.  De esta manera encontramos puntos débiles dentro de los servicios de la empresa y desarrollamos planes de acción.

Este trabajo incluye la carga de una base de datos anteriormente depurada, procediendo a la transformación y codificación de la misma; esto con el propósito de desarrollar modelos y entrenamientos que predigan el comportamiento de los clientes.


---

## 🎯 **Metas del Proyecto**

---

*  Procesar y codificar el conjunto de datos para facilitar la detección de patrones.
*  Detectar patrones de comportamiento y correlaciones relevantes en la taza de abandono.
*  Desarrollar modelos de aprendizaje que identifiquen el comportamiento y tendencias de los clientes
*  Predecir el posible abandono de futuros clientes y tomar medidas.
*  Formular conclusiones y recomendaciones que apoyen la toma de decisiones en retención de clientes.

---

## 🛠 **Herramientas y Tecnologías empleadas**

---

*  Lenguaje: Python 3

*  Bibliotecas y manejo de advertencias: pandas, numpy, warnings 

*  Visualización: matplotlib, `seaborn, yellowbrick

*  Preprocesamiento y escalamiento: MinMaxScaler

*  Muestreo y balanceo de clases: SMOTE, NearMiss

*  Modelos y algoritmos: DecisionTreeClassifier, KNeighborsClassifier, RandomForestClassifier, RandomForestRegressor, DummyRegressor

*  Validación y optimización de modelos: train_test_split, StratifiedKFold, KFold, cross_validate, GridSearchCV

---

## 🔍 **Aspectos Analizados**

---

*  Distribución general de abandono en la base de clientes.

*  Distintos modelos de aprendizaje y normalización de la información.

*  Influencia de las variables dentro de los modelos y el testing

*  Correlaciones entre las variables y su peso final.

*  Análisis con gráficas de Boxplot, Histogramas, Matrices de confusión y Curvas ROC

---

## 💡 **Principales Conclusiones**

---

*  Los contratos mensuales presentan mayor riesgo de cancelación, mientras que los clientes a largo plazo son mas fieles..

*  Existe una inconformidad de los usuarios por el servicio de pago digital y la fibra optica.

*  Los primeros meses son el periodo más crítico para la retención.

## 📅 **Estado del Proyecto**

Finalizado en:  Agosto 19 del 2025

# :alien: **Autoría** 
Carlos de Jesús Gomez Torres
