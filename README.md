# 📊 Análisis de Datos

Este repositorio contiene un **Jupyter Notebook** dedicado al **análisis exploratorio de datos (EDA)** aplicado al dataset de **enfermedades cardíacas (Heart Disease – Cleveland Dataset)**. El enfoque principal es comprender el comportamiento de las variables, identificar patrones relevantes y extraer conclusiones apoyadas en estadísticas descriptivas y visualizaciones.

Este notebook continúa de forma natural la etapa de procesamiento y limpieza de datos, avanzando hacia un análisis más profundo orientado a la **interpretación de resultados**.

---

## 📌 Contenido del Notebook

El archivo principal del repositorio es:

* `Analisis de Datos.ipynb`

En él se desarrollan las siguientes secciones:

---

## 1️⃣ Importación de librerías

Se utilizan librerías estándar para análisis de datos en Python:

* `pandas` para manipulación de datos
* `matplotlib` y `seaborn` para visualización

---

## 2️⃣ Carga del dataset

Se carga el dataset previamente preparado correspondiente al **Heart Disease Dataset (Cleveland)**, el cual contiene información clínica y demográfica de pacientes.

El conjunto de datos incluye variables como:

* Edad
* Sexo
* Tipo de dolor en el pecho
* Presión arterial
* Colesterol
* Frecuencia cardíaca máxima
* Indicadores electrocardiográficos
* Diagnóstico de enfermedad cardíaca (variable objetivo)

---

## 3️⃣ Análisis descriptivo

Se realiza un análisis estadístico básico que permite:

* Obtener medidas de tendencia central (media, mediana)
* Analizar dispersión y rangos
* Detectar posibles valores atípicos

Este análisis ofrece una primera visión cuantitativa del comportamiento de las variables.

---

## 4️⃣ Análisis univariado

Se estudia cada variable de forma individual mediante:

* Histogramas
* Gráficos de barras
* Distribuciones de frecuencia

El objetivo es entender la forma y distribución de los datos.

---

## 5️⃣ Análisis bivariado

Se analizan relaciones entre variables, especialmente frente a la variable objetivo (presencia o ausencia de enfermedad cardíaca):

* Comparaciones por sexo
* Relación entre edad y diagnóstico
* Influencia de variables clínicas sobre la enfermedad

Las visualizaciones permiten identificar patrones y posibles correlaciones.

---

## 6️⃣ Visualización de datos

El notebook hace uso extensivo de gráficos para facilitar la interpretación:

* Gráficos de barras
* Histogramas
* Boxplots
* Gráficos comparativos

Las visualizaciones refuerzan el análisis y ayudan a comunicar hallazgos clave.

---

## 🎯 Objetivo del proyecto

El objetivo principal es **analizar e interpretar datos reales del ámbito de la salud**, aplicando técnicas de análisis exploratorio para:

* Comprender el comportamiento de las variables
* Identificar factores asociados a enfermedades cardíacas
* Sentar las bases para futuros modelos predictivos

---

## 🛠️ Requisitos

Para ejecutar el notebook se requiere:

* Python 3.8 o superior
* Jupyter Notebook o Jupyter Lab
* Librerías:

  ```bash
  pip install pandas matplotlib seaborn
  ```

---

## ▶️ Cómo ejecutar el proyecto

1. Clona el repositorio:

   ```bash
   git clone <url-del-repositorio>
   ```

2. Accede al directorio del proyecto:

   ```bash
   cd <nombre-del-repositorio>
   ```

3. Abre el notebook:

   ```bash
   jupyter notebook
   ```

4. Ejecuta las celdas en orden para reproducir el análisis.

---

## 📚 Dataset

Los datos utilizados provienen del **UCI Machine Learning Repository – Heart Disease Dataset (Cleveland)**, uno de los conjuntos de datos más utilizados en estudios de ciencia de datos y machine learning.

---

## ✍️ Autor

**Johan Suarez**

---

## 📄 Licencia

Este proyecto se distribuye con fines educativos y académicos. Puedes reutilizarlo y adaptarlo libremente citando la fuente.

---

⭐ Si este repositorio te resulta útil, considera darle una estrella en GitHub.
