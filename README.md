# Análisis Estadístico de Consumo y Segmentación de Clientes: ConnectaTel 📊

Este proyecto realiza un análisis profundo de los patrones de consumo y el comportamiento de los usuarios de la empresa de telecomunicaciones *ConnectaTel*. A través de la limpieza de datos, el tratamiento de valores atípicos (outliers) y la segmentación demográfica, se extraen conclusiones clave para optimizar la oferta comercial de la compañía.

## 🎯 Objetivo del Proyecto
El objetivo principal es transformar datos crudos de telecomunicaciones en *insights accionables*. Se busca identificar cómo interactúan los usuarios con sus planes actuales, detectar barreras de consumo y proponer recomendaciones estratégicas para mejorar la retención y el ticket promedio por usuario.

## 📁 Datasets Utilizados
Se utilizaron dos fuentes de datos principales:
1.  *users*: Información demográfica de los usuarios (ID, nombre, edad, ciudad, fecha de registro y fecha de baja).
2.  *usage*: Datos transaccionales de consumo (cantidad de llamadas, mensajes enviados, duración en minutos y fecha de la actividad).

## 🛠️ Etapas del Análisis
El proyecto se dividió en las siguientes fases técnicas:
1.  *Limpieza y Preprocesamiento*: 
    - Identificación y tratamiento de valores nulos (11% en ciudades, 55% en duración de llamadas mediante imputación).
    - Corrección de inconsistencias temporales (filtrado de fechas futuras con la mediana del 2024).
2.  *Análisis Estadístico*: 
    - Visualización de distribuciones mediante histogramas y boxplots.
    - Identificación de outliers mediante el método de Rango Intercuartílico (IQR).
3.  *Segmentación de Clientes*:
    - Creación de categorías por *Uso* (Bajo, Medio, Alto) y por *Edad* (Joven, Adulto, Adulto Mayor).
4.  *Generación de Insights*: 
    - Análisis comparativo entre el *Plan Básico* y el *Plan Premium*.

## 🚀 Cómo ejecutar el Notebook
Para visualizar y ejecutar este análisis, sigue estos pasos:

1.  *Abrir en Google Colab*: 
    - Haz clic en el botón "Open in Colab" (si está disponible) o sube el archivo .ipynb directamente a [Google Colab](https://colab.research.google.com/).
2.  *Instalar dependencias*: El notebook utiliza librerías estándar de Python:
    python
    import pandas as pd
    import numpy as np
    import matplotlib.pyplot as plt
    import seaborn as sns
    
3.  *Carga de datos*: Asegúrate de tener los archivos CSV en la misma carpeta que el notebook o cargarlos en el entorno de Colab.
4.  *Ejecutar todas las celdas*: Ve a Entorno de ejecución > Ejecutar todas.

## 📈 Conclusiones Principales
- *Barreras Psicológicas*: Los usuarios del Plan Básico limitan su consumo drásticamente al acercarse a los 500 minutos para evitar cargos extra.
- *Punto de Convergencia*: La mayoría de los clientes realizan entre 40 y 80 llamadas al mes, independientemente de su plan.
- *Oportunidad de Negocio: Existe un potencial de *upselling para los usuarios que se encuentran en el límite del plan básico, ofreciéndoles los beneficios de la "paz mental" del plan Premium.

---
*Análisis realizado por:* [Tu Nombre]
