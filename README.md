# Análisis Estadístico y Predicción de Rendimiento en Col (Brassica oleracea)

## Descripción del Proyecto
Este repositorio contiene un flujo de trabajo completo de análisis de datos enfocado en evaluar y predecir el rendimiento agrícola basándose en tratamientos experimentales (Fertilización Nitrogenada y Acolchado). El proyecto utiliza datos históricos de campo para identificar prácticas agronómicas óptimas e implementa un modelo de Machine Learning para estimar la biomasa utilizando sensores no destructivos.

## Estructura del Proyecto
* `data/`: Conjunto de datos crudos (raw dataset) provenientes de experimentos de campo (.csv).
* `notebooks/`: Jupyter Notebook que contiene la lógica de limpieza, procesamiento y modelado de datos.
* `images/`: Visualizaciones generadas, incluyendo diagramas de caja (boxplots) y análisis de regresión.

## Características Clave
1. **Ingeniería de Datos:** Pipeline de limpieza automatizada para detectar y eliminar valores atípicos (outliers) de registros manuales de campo.
2. **Análisis Experimental:** Evaluación del impacto de dosis de 125 kg/ha de Nitrógeno vs. Grupos Testigo, estableciendo al "Suelo Desnudo" como el tratamiento de mayor rendimiento bajo las condiciones probadas.
3. **Modelado Predictivo:** Modelo de Regresión Lineal que correlaciona el Índice de Vegetación de Diferencia Normalizada (NDVI) con la biomasa del cultivo, logrando un R-cuadrado (R²) de 0.80.
4. ### Visualización de Resultados

**1. Distribución de Rendimiento por Tratamiento**
![Boxplot de Rendimiento](images/TU_ARCHIVO_DEL_BOXPLOT.png)
*(Aquí se observa cómo el suelo desnudo supera al acolchado en las condiciones del estudio)*

**2. Predicción de Cosecha con IA**
![Regresión Lineal](images/TU_ARCHIVO_DE_REGRESION.png)
*(Modelo predictivo con R²=0.80 correlacionando NDVI y Biomasa)*

## Instalación y Uso
Para replicar este análisis:

1. Clonar el repositorio.
2. Instalar las dependencias requeridas:
   pip install -r requirements.txt
3. Ejecutar el notebook ubicado en el directorio `notebooks/`.

## Tecnologías Utilizadas
* Python 3.x
* Pandas & NumPy (Manipulación de Datos)
* Scikit-Learn (Machine Learning)
* Seaborn & Matplotlib (Visualización)

## Autor
Miguel Angel Lopez Veloz

Estudiante de Ingeniería en Desarrollo de software | Entusiasta del Análisis de Datos

