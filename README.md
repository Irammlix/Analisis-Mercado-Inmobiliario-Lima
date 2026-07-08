# Análisis del Mercado Inmobiliario de Lima Metropolitana

### Dashboard de analítica inmobiliaria para la identificación de oportunidades de inversión

Proyecto desarrollado para analizar el comportamiento del mercado inmobiliario de Lima Metropolitana mediante técnicas de análisis descriptivo, diagnóstico y predictivo.

---

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Microsoft Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)

---
##  📊 Vista General del Dashboard

<img width="4320" height="2430" alt="dashboard_general" src="https://github.com/user-attachments/assets/c86e1d27-720f-48e9-86bc-5d2551684622" />

---
# Contexto del Problema

El mercado inmobiliario de Lima Metropolitana presenta una gran diversidad de inmuebles con características físicas, ubicaciones y niveles de valorización muy distintos entre sí. Esta heterogeneidad dificulta comparar propiedades y determinar si un inmueble se encuentra correctamente valorado dentro de su distrito.

Asimismo, la existencia de diferencias significativas en el precio por metro cuadrado entre distritos hace necesario contar con mecanismos que permitan analizar el comportamiento del mercado de manera objetiva. En este escenario, la disponibilidad de datos inmobiliarios representa una oportunidad para comprender mejor la dinámica del mercado e identificar patrones asociados a la valorización de los inmuebles.

El análisis de información relacionada con precios, ubicación, área construida, antigüedad y características estructurales permite generar evidencia útil para la evaluación de inmuebles y la identificación de posibles oportunidades dentro del mercado inmobiliario.

---

# 🎯 Objetivos

## Objetivo General

Analizar el mercado inmobiliario de Lima Metropolitana para identificar patrones de valorización y detectar oportunidades potenciales de inversión mediante técnicas de analítica de datos y modelos predictivos.

## Objetivos Específicos

### 1. Analizar la distribución y composición de la oferta inmobiliaria en Lima Metropolitana.

Esto permite comprender cómo está conformado el mercado antes de realizar análisis más específicos sobre precios y valorización.

### 2. Identificar los distritos con mayor oferta y valorización inmobiliaria.

Gracias a ello es posible reconocer las zonas con mayor actividad inmobiliaria y los niveles de valorización predominantes dentro del mercado.

### 3. Analizar la influencia de variables como área construida, antigüedad, número de baños y cocheras sobre el precio de los inmuebles.

Esto permite identificar cuáles son las características que tienen una mayor relación con la valorización de una propiedad.

### 4. Detectar inmuebles potencialmente subvalorados mediante el análisis del precio por metro cuadrado respecto a su distrito.

De esta manera se pueden identificar propiedades cuyo valor se encuentra por debajo del comportamiento esperado de su zona.

### 5. Desarrollar un modelo predictivo capaz de estimar el precio de los inmuebles a partir de sus características estructurales y de ubicación.

Esto complementa el análisis descriptivo mediante una estimación del valor esperado de cada inmueble utilizando técnicas de Machine Learning.

# Dataset

## Descripción General

El dataset utilizado contiene información de inmuebles residenciales ubicados en Lima Metropolitana durante el año 2019.

Luego del proceso de depuración y preparación de datos, la base utilizada para el análisis estuvo conformada por 935 inmuebles distribuidos en 23 distritos.

## Variables Analizadas

Para el desarrollo del proyecto se utilizaron variables relacionadas con las características físicas, ubicación y valorización de los inmuebles, entre las que destacan:

- Precio de venta
- Área construida (m²)
- Área total (m²)
- Distrito
- Dormitorios
- Número de baños
- Cocheras
- Antigüedad
- Tipo de inmueble
- Precio por metro cuadrado (S/ m²)

Adicionalmente, la base incluía información complementaria relacionada con amenidades y características específicas de los inmuebles, las cuales fueron consideradas durante la etapa de exploración y modelado.

## Preparación de Datos

Antes del análisis se realizaron actividades de limpieza y validación de datos, incluyendo:

- Revisión de registros inconsistentes.
- Verificación de coordenadas geográficas.
- Detección de valores atípicos.
- Creación de variables derivadas como precio por metro cuadrado.
- Estandarización de atributos utilizados en el análisis y modelado predictivo.

# 🛠 Metodología

## Metodología Rollins

El desarrollo del proyecto se realizó siguiendo la metodología Rollins de 10 etapas para proyectos de Ciencia de Datos, permitiendo estructurar el proceso desde la comprensión del problema hasta la visualización y generación de hallazgos.

| Etapa | Aplicación en el proyecto |
|---------|---------|
| Comprensión del Negocio | Se identificó la necesidad de analizar el mercado inmobiliario e identificar oportunidades potenciales de inversión. |
| Enfoque Analítico | Se definió un enfoque descriptivo, diagnóstico y predictivo para estudiar el comportamiento del mercado. |
| Requerimientos de Datos | Se determinaron las variables necesarias para el análisis, incluyendo precio, área construida, área total, distrito, dormitorios, baños y cocheras. |
| Recolección de Datos | Se trabajó con una base de datos de inmuebles residenciales ubicados en Lima Metropolitana. |
| Comprensión de los Datos | Se realizó un análisis exploratorio para identificar patrones, distribuciones y posibles inconsistencias. |
| Preparación de los Datos | Se efectuó limpieza de datos, tratamiento de registros inconsistentes y creación de variables derivadas como el precio por metro cuadrado. |
| Modelado | Se aplicaron técnicas de visualización, análisis comparativo y modelos predictivos mediante Regresión Lineal y Random Forest. |
| Evaluación | Se evaluó el desempeño del modelo predictivo mediante las métricas R² y Error Absoluto Medio (MAE). |
| Despliegue | Los resultados fueron implementados en un dashboard interactivo desarrollado en Power BI. |
| Retroalimentación | Se identificaron oportunidades de mejora relacionadas con la incorporación de nuevas variables y técnicas predictivas más avanzadas. |

# 📊 Dashboard

El dashboard fue desarrollado en Power BI y se estructuró en cinco secciones principales que permiten comprender progresivamente el comportamiento del mercado inmobiliario, identificar factores asociados a la valorización de los inmuebles y detectar oportunidades de inversión.

---

## 🏠 Panorama del Mercado Inmobiliario

<img width="1535" height="861" alt="panorama" src="https://github.com/user-attachments/assets/54f47efe-3bf8-4e24-bdb6-f6435087667f" />

### ¿Qué buscábamos?

Tener una visión general del mercado inmobiliario analizado antes de profundizar en los factores asociados al precio de los inmuebles.

### ¿Qué analizamos?

La cantidad de inmuebles disponibles, los precios representativos del mercado, la distribución geográfica de la oferta y los principales tipos de vivienda presentes en la muestra.

### ¿Qué encontramos?

La muestra estuvo conformada por 935 inmuebles distribuidos en 23 distritos. Además, se observó que la oferta inmobiliaria se encuentra compuesta principalmente por viviendas tipo casa.

---

## 📊 Mercado y Valorización Inmobiliaria

<img width="1535" height="863" alt="mercado" src="https://github.com/user-attachments/assets/76dcc88f-6cf4-473e-9eec-5c3b14f67aa6" />

### ¿Qué buscábamos?

Comprender cómo se distribuye la oferta inmobiliaria entre los distintos distritos y cuáles presentan mayores niveles de valorización.

### ¿Qué analizamos?

La cantidad de inmuebles por distrito, el precio mediano por metro cuadrado y la variabilidad de precios observada dentro de cada zona.

### ¿Qué encontramos?

Distritos como La Molina concentran una gran cantidad de inmuebles y presentan una alta dispersión en el precio por metro cuadrado, evidenciando una oferta inmobiliaria heterogénea.

---

## 📈 Factores del Precio

<img width="1535" height="861" alt="factores" src="https://github.com/user-attachments/assets/687dab41-0e16-4d88-ba1c-e6ce0cd91aea" />

### ¿Qué buscábamos?

Identificar las características que presentan una mayor relación con el valor de los inmuebles.

### ¿Qué analizamos?

Variables como área construida, antigüedad, número de baños y cantidad de cocheras, observando cómo estas se relacionan con el precio de venta y el valor por metro cuadrado.

### ¿Qué encontramos?

El área construida mostró una relación positiva con el precio de venta. Asimismo, los inmuebles con mayor cantidad de baños y cocheras suelen registrar mayores valores por metro cuadrado.

---

## 🚨 Oportunidades de Inversión

<img width="1530" height="858" alt="oportunidades" src="https://github.com/user-attachments/assets/397a15bc-fe10-4cd6-8b96-0fefee8e4126" />

### ¿Qué buscábamos?

Encontrar inmuebles que pudieran representar oportunidades de inversión dentro del mercado inmobiliario.

### ¿Qué analizamos?

Comparamos el precio por metro cuadrado de cada inmueble con el comportamiento habitual de su distrito utilizando como referencia la mediana distrital.

### ¿Qué encontramos?

Se identificaron 462 inmuebles cuyos precios se encontraban por debajo del comportamiento esperado de su zona, destacando principalmente distritos como La Molina y Santiago de Surco.

---

## 🤖 Modelo Predictivo de Valoración Inmobiliaria

<img width="1532" height="862" alt="analisis" src="https://github.com/user-attachments/assets/0affb4fd-60d7-49af-a5af-83d241b0af8c" />

### ¿Qué buscábamos?

Explorar si era posible estimar el precio de una vivienda a partir de sus características físicas y de ubicación.

### ¿Qué analizamos?

Se construyeron modelos predictivos utilizando variables como área construida, área total, distrito, antigüedad, tipo de inmueble, dormitorios, baños y cocheras.

### ¿Qué encontramos?

El modelo Random Forest alcanzó un R² de 0.4030 y permitió identificar 534 inmuebles cuyo precio observado era inferior al precio estimado por el modelo, sugiriendo posibles oportunidades de inversión desde una perspectiva predictiva.


# Análisis Predictivo

Como complemento al análisis descriptivo y diagnóstico realizado previamente, se exploró la posibilidad de estimar el precio de los inmuebles mediante técnicas de Machine Learning.

Para ello se desarrollaron modelos predictivos utilizando variables como área construida, área total, distrito, tipo de inmueble, antigüedad, dormitorios, baños y cocheras.

Entre los modelos evaluados se probaron enfoques de Regresión Lineal y Random Forest, obteniendo mejores resultados con este último.

## Resultados

- R² = 0.4030
- MAE ≈ 330 442 soles

## Aprendizajes obtenidos

Los resultados evidenciaron que variables estructurales como el área construida, el distrito y la antigüedad explican parte importante del comportamiento del precio. Sin embargo, también sugieren la existencia de otros factores relevantes no presentes en la base de datos, tales como ubicación específica, acabados o estado de conservación.

Por ello, el modelo predictivo fue utilizado como una herramienta complementaria para apoyar la identificación de oportunidades de inversión y no como un mecanismo definitivo de valoración.

# 📌 Hallazgos Principales

- La muestra analizada estuvo conformada por 935 inmuebles distribuidos en 23 distritos de Lima Metropolitana.

- Las viviendas tipo casa representaron la mayor parte de la oferta inmobiliaria observada.

- Distritos como La Molina y Santiago de Surco concentraron una parte importante de la oferta inmobiliaria analizada.

- El área construida presentó una relación positiva con el precio de venta, consolidándose como uno de los factores más relevantes en la valorización de los inmuebles.

- Los inmuebles con mayor cantidad de baños y cocheras tendieron a registrar mayores valores por metro cuadrado.

- Se identificaron 462 inmuebles potencialmente subvalorados mediante la comparación de su precio por metro cuadrado con la referencia de su distrito.

- Distritos como La Molina y Santiago de Surco concentraron una gran cantidad de oportunidades de inversión detectadas.

- El análisis predictivo permitió identificar 534 inmuebles cuyo precio observado era inferior al estimado por el modelo, generando una segunda perspectiva para la evaluación de oportunidades inmobiliarias.

# Conclusiones

### 1. El mercado inmobiliario presenta una alta heterogeneidad entre distritos.

Los resultados mostraron diferencias significativas en la oferta y valorización de los inmuebles, evidenciando que la ubicación continúa siendo uno de los factores más relevantes dentro del mercado inmobiliario de Lima Metropolitana.

### 2. Las características físicas del inmueble influyen directamente en su valorización.

Variables como el área construida, el número de baños y la cantidad de cocheras mostraron una relación positiva con el precio de venta, confirmando su importancia dentro del proceso de valoración inmobiliaria.

### 3. Es posible identificar oportunidades de inversión mediante el análisis de datos.

La comparación entre el precio por metro cuadrado de cada inmueble y el comportamiento de su distrito permitió detectar 462 propiedades potencialmente subvaloradas, ofreciendo una metodología objetiva para reducir el universo de búsqueda de posibles inversiones.

### 4. El análisis predictivo complementa la evaluación del mercado.

Aunque el modelo predictivo no explica completamente la variabilidad de los precios, permitió generar una segunda perspectiva para la detección de oportunidades y evidenció la existencia de factores adicionales que podrían incorporarse en futuras investigaciones.

