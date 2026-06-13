# Taller No. 3: Análisis Estadístico Descriptivo y Visualización de Datos
**Asignatura:** Inteligencia Artificial (Semestre 8 - Corte II)  
**Institución:** Universidad del Pacífico - Programa de Ingeniería de Sistemas  
**Estudiante:** Elkin Chalarca  

---

## 📋 Descripción del Proyecto
Este repositorio contiene el desarrollo del análisis estadístico descriptivo realizado sobre el conjunto de datos de descargas de aplicaciones móviles. El objetivo principal es aplicar técnicas estadísticas y computacionales para transformar datos crudos en información útil, apoyando la toma de decisiones estratégicas mediante representaciones gráficas e interpretaciones técnicas.

La variable analizada de forma objetiva y principal en este estudio es **'Apps Descargadas'**.

---

## 📊 Resumen Estadístico Inicial
A partir de la muestra de $N = 50$ observaciones del conjunto de datos, se determinaron los siguientes parámetros métricos fundamentales:

* **Valor Mínimo ($Min$):** 30 apps
* **Valor Máximo ($Max$):** 132 apps
* **Rango ($R$):** 102
* **Número de Intervalos ($k$):** 7 (Calculado mediante la Regla de Sturges: $k = 1 + 3.322 \cdot \log_{10}(50)$)
* **Amplitud de Clase ($A$):** 15 (Aproximado para manejo de variables discretas)

---

## 🧮 Tabla de Distribución de Frecuencias

| Intervalo | Lím. Inferior | Lím. Superior | Marca de Clase ($X_i$) | Frec. Absoluta ($f_i$) | Frec. Relativa ($h_i$) | Frec. Acumulada ($F_i$) | Frec. Relat. Acumulada ($H_i$) |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| **1** | 30 | 45 | 37.5 | 7 | 14% | 7 | 14% |
| **2** | 45 | 60 | 52.5 | 6 | 12% | 13 | 26% |
| **3** | 60 | 75 | 67.5 | 10 | 20% | 23 | 46% |
| **4** | 75 | 90 | 82.5 | 9 | 18% | 32 | 64% |
| **5** | 90 | 105 | 97.5 | 9 | 18% | 41 | 82% |
| **6** | 105 | 120 | 112.5 | 4 | 8% | 45 | 90% |
| **7** | 120 | 135 | 127.5 | 5 | 10% | 50 | 100% |

---

## 📈 Visualizaciones Incluidas (En el Informe)
El análisis cuenta con tres representaciones gráficas estructuradas bajo estándares técnicos de presentación:
1. **Histograma de Frecuencias:** Muestra la distribución del volumen de usuarios según sus rangos de descarga, evidenciando un comportamiento con tendencia central.
2. **Polígono de Frecuencias:** Construído a partir de las marcas de clase ($X_i$) para modelar el comportamiento continuo de la distribución.
3. **Ojiva (Curva Acumulada):** Gráfico ascendente clave para identificar percentiles y la velocidad de acumulación de los datos para la toma de decisiones.

---

## 🧠 Conclusiones Clave del Análisis
* **Concentración:** El rango de mayor acumulación de usuarios se encuentra entre las **60 y 75 descargas**, representando el 20% total de la muestra.
* **Comportamiento:** La distribución presenta rasgos similares a una **distribución normal**, con una ligera asimetría hacia el extremo de alta descarga.
* **Segmentación:** El **46%** de los usuarios se encuentra por debajo de las 75 descargas, aislando un **18%** de superusuarios que superan las 105 descargas, ideal para estrategias comerciales enfocadas en nichos específicos.

---

## 📂 Estructura del Repositorio
* `/Taller_analisis_estadistico_frecuencia_grficos.pdf`: Informe escrito formal en formato PDF con la interpretación técnica rigurosa.
* `/Taller_destadistica_descritiva-frecuencias.xlsx`: Hoja de cálculo de Excel que contiene la matriz de datos original, las fórmulas aplicadas y los gráficos interactivos generados.
* `/README.md`: Archivo de presentación actual.
