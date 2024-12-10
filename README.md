# Análisis Predictivo de Supervivencia en el Titanic
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-0.24%2B-orange)
![Pandas](https://img.shields.io/badge/Pandas-1.2%2B-green)

## Descripción
Este proyecto realiza un análisis exhaustivo de los factores que influyeron en la supervivencia de los pasajeros del Titanic, utilizando técnicas de machine learning, específicamente árboles de decisión. El análisis combina exploración de datos, técnicas estadísticas avanzadas y visualizaciones detalladas para comprender los patrones de supervivencia.

## Características del Análisis
El estudio examina múltiples aspectos de los datos del Titanic:

- Características socioeconómicas (clase del pasajero, tarifa pagada)
- Factores demográficos (edad, género)
- Relaciones familiares (hermanos/cónyuges, padres/hijos a bordo)
- Punto de embarque
- Títulos y estatus social derivados de los nombres

## Metodología
El análisis sigue una estructura rigurosa:

1. **Análisis Exploratorio de Datos**
   - Visualización de distribuciones
   - Análisis de valores faltantes
   - Identificación de correlaciones
   - Detección de valores atípicos

2. **Preprocesamiento**
   - Manejo de valores faltantes mediante técnicas estadísticas
   - Codificación de variables categóricas
   - Creación de nuevas características
   - Normalización de datos numéricos

3. **Selección de Características**
   - Aplicación de ANOVA F-value
   - Identificación de las variables más significativas
   - Reducción de dimensionalidad

4. **Modelado Predictivo**
   - Implementación de árboles de decisión
   - Optimización de hiperparámetros
   - Validación cruzada
   - Evaluación de resultados

## Resultados Principales
- Identificación de los factores más influyentes en la supervivencia
- Desarrollo de un modelo predictivo con 87% de precisión
- Visualizaciones interactivas de patrones de supervivencia
- Análisis detallado de la importancia de las características

## Tecnologías Utilizadas
- Python 3.8+
- pandas y numpy para manipulación de datos
- scikit-learn para modelado predictivo
- matplotlib y seaborn para visualizaciones
- Jupyter Notebook para desarrollo interactivo

## Instalación y Uso
1. Clone el repositorio:
```bash
git clone https://github.com/Jaycoach/DecisionTree_Titanic.git