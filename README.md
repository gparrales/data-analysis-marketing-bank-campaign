# data-analysis-marketing-bank-campaign
## Descripción / Overview

Analiza el desempeño de una campaña de marketing directo de una entidad financiera orientada a la captación de inversiones a plazo fijo. A través de un proceso de análisis exploratorio de datos (EDA) y limpieza de datos, se procesaron más de 41,000 registros para identificar los factores críticos que impulsan la conversión de clientes.

---

## Problema de negocio:

Los equipos comerciales de una entidad financiera buscaban entender qué factores influyen en la probabilidad de que un cliente acepte una oferta tras una llamada telefónica.

---

## Conjuntos de datos: 

El dataset contiene información demográfica y financiera de los clientes del banco, así como también información de las interacciones (llamadas) como duración de la llamada, contactos previos y cantidad de contactos previos, aceptación del producto, etc.

---

## Objetivos del Proyecto:

- Determinar la efectividad de la campaña (tasa de conversión).
- Identificar el perfil del cliente "buyer persona".
- Detectar patrones de comportamiento.
- Proponer mejoras para aumentar la efectividad de futuras campañas.
- Visualización de insights accionables (Power BI) relevantes para la toma de decisiones.

---

## Limpieza y preparación de datos:

Durante la etapa de preprocesamiento se realizaron las siguientes acciones:
- Eliminación del 11,2 % de registros con información incompleta o inconsistente.
- Revisión de tipos de datos y corrección de variables categóricas.
- Análisis de valores atípicos en variables numéricas.
- Comparación de dos métodos diferentes de imputación en valores atípicos: reemplazo por mediana y capping.
- Preparación del dataset final para análisis exploratorio y visualización.

---

## Análisis exploratorio de datos

El análisis permitió identificar patrones relevantes en el comportamiento de los clientes. Los hallazgos más relevantes son:
- Tasa de conversión general: 11,25 % de los clientes contactados aceptaron el producto financiero.
- Duración de llamada óptima: Las llamadas con duración entre 3 y 6 minutos presentan mayor probabilidad de conversión.
- Perfil con mayor probabilidad de conversión (Buyer Persona): Edad entre 30 y 39 años, sin préstamos personales activos pero si hipotecas,
  sin morosidad, casados y estudios universitarios.
- Canal de contacto con mayor efectividad.
- Contactos más eficientes en meses específicos de campaña activa

---

## Visualización y Dashboard

Se desarrolló un dashboard informativo en Power BI para mostrar resultados a áreas comerciales y de marketing.
El dashboard permite:

- Analizar la conversión por segmento demográfico
- Evaluar el desempeño por mes y tipo de contacto
- Identificar combinaciones de variables con mayor probabilidad de éxito
- Explorar la relación entre duración de llamada y conversión

---

## Conclusiones de negocio

A partir del análisis se proponen las siguientes recomendaciones:

- Priorizar segmentos de clientes en base al "buyer persona".
- Optimizar la duración de las llamadas dentro del rango de mayor efectividad.
- Utilizar el canal de ventas (línea móil) con mayor aceptación.
- Planificar campañas en meses con mejor desempeño histórico.

---

## Informe:

Se adjunta un informe (PDF) en el que se detalla el análisis de una campaña de marketing directo para captación de inversiones a plazo fijo en una entidad financiera. En el documento se detallan aspectos técnicos sobre EDA, métodos de imputación, así como análisis de variables, en la parte final se incluyen insights y recomendaciones en base a los resultados encontrados.

---

## Estructura:

- Datos/: CSV con datos de la última campaña realizada
- Notebooks/: Jupyter Notebook (Colab)
- Documentos/: informe en formato pdf
- Tecnologías: Python, Pandas, Matplotlib, Seaborn, Power BI.

Puedes visualizar el dashboard en: https://app.powerbi.com/view?r=eyJrIjoiMjQxMmEyNWYtNDJiOC00Mjk4LTgzNTAtOWM1ZTEzYjc5OTUzIiwidCI6IjNhYTQwMmY0LTc1ZDktNDc0ZS1iZTU2LTcyMmMyMzM5Mjc4ZCIsImMiOjR9
