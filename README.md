# Análisis Multivariado

Hola a todos :) Este repositorio será una colección de implementaciones, ejemplos y documentación sobre técnicas de análisis multivariado aplicadas a ciencia de datos, estadística aplicada y machine learning. Actualmente y por falta de tiempo, el repositorio está en fase de desarrollo inicial. El objetivo es construir una referencia técnica completa, con fundamentos matemáticos y ejemplos prácticos de cada técnica multivariada.

## Contenido

- **Introducción al Análisis Multivariado**  
- **Técnicas de Reducción de Dimensionalidad**  
  - Análisis de Componentes Principales (PCA)
  - Análisis Factorial
  - t-SNE, UMAP
- **Modelado Multivariado**
  - Regresión Múltiple
  - MANOVA
  - Modelos de Ecuaciones Estructurales (SEM)
- **Análisis de Agrupamiento**
  - K-means
  - Clustering Jerárquico
  - DBSCAN
- **Dependencias y Correlaciones**
  - Correlación Canónica
  - Análisis de Correspondencias
- **Visualización Multivariada**
  - Biplots
  - Heatmaps
  - Matrices de dispersión

## Objetivo

El objetivo principal de este repositorio es servir como referencia técnica para la aplicación práctica de técnicas multivariadas, explicando:

- Fundamentos matemáticos y estadísticos de cada método.
- Casos de uso en ciencia de datos.
- Interpretación correcta de resultados.
- Ejemplos implementados en Python (y eventualmente R).

## Fundamento Matemático

Cada técnica se documentará con su respectiva formulación matemática:

- Matrices de covarianza y correlación.
- Autovalores y autovectores.
- Descomposición espectral y SVD.
- Modelos lineales multivariados.

Se priorizará el **rigor matemático** con una explicación **sencilla e intuitiva**.

## Herramientas Utilizadas

- Python 3.10+
- Librerías:
  - `numpy`, `scipy`
  - `scikit-learn`
  - `statsmodels`
  - `matplotlib`, `seaborn`
  - `pingouin`, `prince`

## Estructura del Repositorio

```
📂 analisis-multivariado/
├── 📜 README.md
├── 📂 notebooks/
│   ├── PCA.ipynb
│   ├── Clustering.ipynb
│   └── MANOVA.ipynb
├── 📂 src/
│   ├── pca.py
│   ├── clustering.py
│   └── manova.py
├── 📂 datasets/
│   └── datos_ejemplo.csv
├── 📂 docs/
│   └── fundamentos_teoricos.md
└── requirements.txt
```

## Cómo Empezar

1. Clona el repositorio:
   ```bash
   git clone https://github.com/oriolgilabertlopez/analisis-multivariado.git
   cd analisis-multivariado
   ```
2. Instala las dependencias:
   ```bash
   pip install -r requirements.txt
   ```

3. Ejecuta los notebooks o scripts disponibles.
