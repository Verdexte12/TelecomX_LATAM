# TelecomX_LATAM

## 📌 Descripción del proyecto

Este repositorio contiene el análisis completo de Churn (rotación de clientes) para una empresa de telecomunicaciones, desarrollado como parte del Challenge ONE de Data Science. El objetivo principal es identificar los factores que influyen en la tasa de abandono de clientes y proponer estrategias efectivas para reducirla.

## 🎯 Objetivo

El objetivo principal es recopilar, procesar y analizar datos de clientes utilizando Python y sus bibliotecas principales para extraer información valiosa. Estos insights ayudarán al equipo de Data Science a desarrollar modelos predictivos y estrategias efectivas para reducir la tasa de churn.

## 🔍 Contenido del notebook

El análisis se estructura en las siguientes secciones:

Importación de bibliotecas: Carga de las bibliotecas esenciales para el procesamiento, análisis y visualización de datos (pandas, numpy, matplotlib, seaborn, scipy, requests, json).

Carga y exploración inicial del dataset: Carga del dataset desde una fuente externa (JSON) y normalización de su estructura para facilitar el análisis. Se realiza una exploración inicial para entender la composición de los datos.

Limpieza y preprocesamiento de datos: Pasos de limpieza, manejo de valores nulos y transformaciones necesarias (como mapeo de variables categóricas a numéricas) para preparar los datos.

## Análisis de datos:

-Funciones para calcular la asociación entre variables categóricas.

-Visualización de distribuciones de variables categóricas vs. Churn.

-Visualización de correlaciones.

-Análisis de la relación entre variables numéricas y Churn (boxplots/violin plots).

-Ingeniería de Características: Creación de nuevas variables informativas (NumServices, TenureGroup, PremiumCustomer).

-Análisis de la tasa de Churn por diferentes combinaciones de factores (heatmap interactivo).

-Análisis de la relación entre el Valor de Vida del Cliente (CLV) y el Churn.

-Insights clave: Resumen de los principales hallazgos del análisis, destacando los factores que aumentan y protegen contra el Churn, así como patrones relevantes en variables numéricas y correlaciones.

-Conclusiones y recomendaciones: Interpretación general de los resultados y un conjunto de recomendaciones estratégicas basadas en los insights para reducir el abandono de clientes.


## 🛠️ Herramientas y bibliotecas

Python

-pandas

-numpy

-matplotlib

-json

-plotly (para visualizaciones interactivas)


## 🚀 Cómo ejecutar el código

Clona este repositorio.

Asegúrate de tener instaladas las bibliotecas mencionadas.

Ejecuta las celdas secuencialmente para replicar el análisis.


## 📂 Dataset
El dataset utilizado para este análisis se carga directamente desde una URL de GitHub en formato JSON. Contiene información sobre clientes de Telecom X, incluyendo datos demográficos, servicios contratados, información de cuenta y si el cliente ha abandonado el servicio (Churn).

## ✉️ Autor

Juan Miguel Sanz

## 📝 Licencia

Este proyecto está bajo la Licencia MIT.
