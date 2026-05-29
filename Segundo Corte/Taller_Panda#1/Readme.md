<img width="2874" height="1614" alt="image" src="https://github.com/user-attachments/assets/c64180ba-1e75-4aba-8885-13de42652305" />


## Investigación y Práctica con la Librería Pandas 🐼
Este repositorio contiene una investigación exhaustiva y ejercicios prácticos sobre la librería Pandas de Python, desarrollados en un entorno de Google Colab.
### 📝 Descripción de la actividad
La actividad consiste en explorar las capacidades de Pandas para la manipulación y el análisis de datos, comprendiendo su funcionamiento técnico, sus estructuras principales y su rol crítico dentro del ecosistema de la Ciencia de Datos y la Inteligencia Artificial.
### 🎯 Objetivo
El objetivo primordial es dominar el uso de estructuras de datos bidimensionales (DataFrames) y unidimensionales (Series) para realizar tareas de limpieza, transformación y análisis exploratorio de datos de manera eficiente
.

--------------------------------------------------------------------------------
## 📚 Temas Investigados
### 1. ¿Qué es Pandas?
Pandas es una librería de código abierto (open source) para el lenguaje Python, especializada en el manejo y análisis de estructuras de datos
. Su nombre deriva del término "Panel Data", un concepto de econometría que se refiere a conjuntos de datos organizados
.
### 2. ¿Para qué sirve?
Se utiliza para manipular, modelar, analizar y preparar datos
. Es una herramienta versátil que permite realizar:
Limpieza y tratamiento de datos
.
Análisis Exploratorio de Datos (EDA)
.
Soporte para actividades de Machine Learning
.
Consultas a bases de datos relacionales y visualizaciones
.
### 3. Objetivo principal de la librería
Su propósito es ofrecer un enfoque rápido, flexible y robusto para trabajar con datos relacionales o etiquetados de forma sencilla e intuitiva
. A diferencia de herramientas como Excel, su límite de procesamiento de datos no es fijo, sino que depende de la memoria RAM disponible en el equipo
.
### 4. Principales funciones y características

### Características

- Manejo de grandes cantidades de datos.
- Compatible con archivos CSV y Excel.
- Permite filtrar y ordenar datos.
- Facilita operaciones matemáticas y estadísticas.
- Integración con Inteligencia Artificial y Machine Learning.

### Funciones comunes

| Función | Descripción |
|---|---|
| read_csv() | Leer archivos CSV |
| DataFrame() | Crear tablas de datos |
| head() | Mostrar primeras filas |
| info() | Información del DataFrame |
| describe() | Estadísticas básicas |
| dropna() | Eliminar valores vacíos |
| sort_values() | Ordenar datos |

Estructuras de datos: Maneja dos objetos primarios: Series (unidimensionales, como columnas individuales) y DataFrames (bidimensionales, similares a tablas de bases de datos o Excel)
.
Entrada y salida de datos: Capacidad para leer y escribir en múltiples formatos como CSV, Excel, SQL, JSON, HTML y Parquet
.
Manipulación flexible: Métodos para reordenar, dividir, combinar, filtrar y agrupar conjuntos de datos (groupby)
.
Integración: Excelente compatibilidad con otras librerías como NumPy, Matplotlib y Scikit-Learn
.
### 5. Importancia en IA y Análisis de Datos
Pandas es considerada una herramienta esencial en el flujo de trabajo de la Ciencia de Datos
. Permite la preparación y limpieza de datos necesaria antes de entrenar modelos de Inteligencia Artificial, asegurando que la información sea procesable por los algoritmos
.

--------------------------------------------------------------------------------
# Ejercicio elaborado en colab 
## Tecnologías usadas

- Python
- Pandas
- NumPy
- Google Colab
- GitHub

# Notebook en google Colab

[Abrir Notebook](https://colab.research.google.com/drive/1ikIPmV3-cL6i-18pYQiK2uzvgua2TJgR?usp=sharing)

--------------------------------------------------------------------------------
## 💻 Explicación de los ejercicios realizados
En el Notebook adjunto se desarrollaron los siguientes puntos prácticos:
Creación de un DataFrame: Se generaron tablas de datos a partir de estructuras nativas de Python como diccionarios.

<img width="494" height="359" alt="image" src="https://github.com/user-attachments/assets/991a42d7-1586-4f8f-87a6-17419e4cfbae" />

Operaciones entre columnas: Se realizaron cálculos aritméticos directos entre columnas, como restas o aplicaciones de funciones lambda para transformar valores

<img width="500" height="231" alt="image" src="https://github.com/user-attachments/assets/924d3468-c201-450b-a68b-c52259f66aca" />

Lectura de archivos CSV: Uso del método read_csv para importar conjuntos de datos externos (como el dataset Iris) para su análisis

<img width="491" height="402" alt="image" src="https://github.com/user-attachments/assets/a7460718-7026-470c-a97a-3852cd3063fc" />

Trabajo con datos sintéticos y valores nulos: Se practicó la detección de valores perdidos (NaN) y su tratamiento mediante el llenado de datos con el método fillna()
.

--------------------------------------------------------------------------------
## 📊 Resultados Obtenidos
(Nota: Aquí puedes incluir capturas de pantalla de las tablas resultantes en tu Colab, gráficos generados con .plot() o estadísticas descriptivas obtenidas con el método .describe())
.
💡 Conclusiones
Pandas supera las limitaciones de las hojas de cálculo tradicionales al permitir el manejo de grandes volúmenes de datos mediante programación
.
Su capacidad de integración con el ecosistema de Python la convierte en la puerta de entrada ideal para cualquier proyecto de Ciencia de Datos
.
La comprensión de las Series y DataFrames es fundamental para estructurar correctamente cualquier análisis de información
