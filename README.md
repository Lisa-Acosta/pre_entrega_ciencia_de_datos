📘 Pre-entrega

Autora: Olga Elizabet Acosta

Lenguaje: Python

Entorno: Google Colab

🧩 Descripción General

Este notebook corresponde a la pre-entrega de un trabajo práctico cuyo objetivo principal es demostrar el manejo de herramientas fundamentales de análisis y manipulación de datos con Python, aplicando conceptos de ETL, exploración y limpieza de datos.

🚀 Objetivos

1. Cargar y preparar datasets provenientes de archivos CSV.

2. Explorar y analizar la estructura y estadísticas de los datos.

3. Identificar y tratar valores faltantes, duplicados o inconsistencias.

4. Integrar y transformar datasets para obtener una vista consolidada.

5. Documentar claramente cada etapa del proceso con código y comentarios explicativos.

📂 Estructura del Notebook

| Sección                                             | Descripción                                                                        |
| --------------------------------------------------- | ---------------------------------------------------------------------------------- |
| 🧩 **Etapa 1: Recopilación y Preparación de Datos** | Carga de datasets desde Google Drive y validación de estructura.                   |
| 🔍 **Análisis Exploratorio Inicial**                | Inspección de columnas, tipos de datos, valores nulos y estadísticas descriptivas. |
| 🧹 **Limpieza y Transformación**                    | (si existe) Procesamiento de datos, normalización y combinación entre tablas.      |
| 📈 **Visualización o Resultados**                   | (si aplica) Representación gráfica o resumen final de los hallazgos.               |

🧠 Librerías utilizadas

import pandas as pd
import numpy as np
import os

📊 Datasets

Los archivos utilizados se encuentran en la carpeta:

/content/drive/MyDrive/datasets/


Archivos esperados:

1. clientes.csv

2. ventas.csv

3. marketing.csv


⚙️ Requisitos para ejecutar

Abrir el notebook en Google Colab.


Montar Google Drive:

from google.colab import drive
drive.mount('/content/drive')


Asegurar que los archivos CSV estén en la ruta /content/drive/MyDrive/datasets/.
