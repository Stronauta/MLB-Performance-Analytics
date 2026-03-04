# ⚾ MLB-Performance-Analytics
### Proyecto Final - Módulo 6 | Data Science & Machine Learning

![Python](https://img.shields.io/badge/Python-3.9+-blue?logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-F7931E?logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Library-Pandas-150458?logo=pandas&logoColor=white)
![MLB](https://img.shields.io/badge/Data-MLB%20Statcast-red)

Este repositorio contiene el desarrollo del **Proyecto Final del Módulo 6**, enfocado en la clasificación y análisis del rendimiento ofensivo de jugadores de la MLB utilizando técnicas avanzadas de **Machine Learning**.

## 📋 Descripción del Proyecto

El objetivo principal de este proyecto es demostrar cómo los modelos de Machine Learning pueden identificar patrones complejos en estadísticas de béisbol para diferenciar perfiles ofensivos. 

Para este análisis, desarrollamos tres variables objetivo clave para clasificar a los bateadores:

* **🏆 Rendimiento General:** Evaluación del aporte estándar y consistencia del jugador en el campo.
* **💎 Nivel Elite:** Identificación de jugadores con un desempeño excepcionalmente alto (outliers positivos).
* **👁️ Disciplina en el Plato:** Análisis de la capacidad del bateador para tomar decisiones correctas y su control de la zona de strike.

## 🚀 Características Principales

* **Ingeniería de Variables (Feature Engineering):** Creación de métricas personalizadas a partir de datos brutos de *Statcast* para capturar la esencia del juego.
* **Análisis Multidimensional:** Integración de métricas tradicionales (AVG, HR) con estadísticas avanzadas de última generación.
* **Modelos de Clasificación:** Implementación y optimización de modelos **Random Forest** para determinar qué variables impactan más en el éxito de un bateador.

## 🛠️ Tecnologías Utilizadas

| Herramienta | Uso |
| :--- | :--- |
| **Python** | Lenguaje principal de desarrollo. |
| **Pandas** | Manipulación, limpieza y transformación de datos. |
| **Matplotlib / Seaborn** | Visualización de datos y análisis exploratorio. |
| **Scikit-Learn** | Construcción, entrenamiento y evaluación de modelos de ML. |

## 📊 Visualizaciones

> **Nota:** Aquí puedes ver algunos de los resultados clave obtenidos tras el entrenamiento del modelo.
### 📈 Rendimiento y Disciplina
El análisis comenzó comparando cómo la disciplina en el plato se relaciona con el rendimiento general de los bateadores.

<p align="center">
  <img src="img/disciplina%20en%20plato%20vs%20rendimiento.png" width="600" alt="Disciplina vs Rendimiento">
</p>

### 🧠 Importancia de las Variables (Feature Importance)
Utilizamos modelos de **Random Forest** para identificar qué métricas son las que realmente definen a un jugador en las tres categorías analizadas:

| Disciplina en el Plato | Rendimiento General |
| :---: | :---: |
| <img src="img/Variables%20importante%20en%20la%20disciplina%20plato.png" width="400"> | <img src="img/Variables%20importantes%20para%20saber%20el%20rendimiento%20general.png" width="400"> |

### 💎 Identificación de Jugadores Élite
El modelo permite distinguir qué factores separan a un jugador promedio de uno Élite, destacando métricas como el **wOBA** (Weighted On-Base Average).

<p align="center">
  <img src="img/Variable%20importantes%20en%20determionar%20un%20elite%20o%20no.png" width="700" alt="Variables Elite">
  <br>
  <em>Factores clave para determinar el estatus Elite.</em>
</p>

<p align="center">
  <img src="img/wOba%20en%20jugadores%20Elite%20y%20no%20Elite.png" width="500" alt="wOBA Elite vs No Elite">
</p>


---
📝 **Nota:** Este proyecto fue desarrollado con fines académicos para el Módulo 6 del programa de Ciencia de Datos.
