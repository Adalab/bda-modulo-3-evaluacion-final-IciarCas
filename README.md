Airline Loyalty Program - Data Analytics

Análisis exploratorio y estadístico del programa de fidelidad de una aerolínea, realizado como ejercicio de evaluación final del Módulo 3 de Data Analytics.
Este proyecto analiza el comportamiento de los clientes de un programa de lealtad aéreo a partir de dos datasets:

- **Customer Flight Analysis.csv**: actividad de vuelos mensual por cliente (vuelos reservados, distancia, puntos acumulados/redimidos).
- **Customer Loyalty History.csv**: perfil demográfico y de membresía de cada cliente (ubicación, educación, salario, tipo de tarjeta, etc.).

## Estructura del proyecto
```
├── data/
│   ├── Customer Flight Analysis.csv
│   └── Customer Loyalty History.csv
├── f1_exploracion_limpieza.ipynb
├── f2_analisis_cats_nums.ipynb
├── f3_visualizacion.ipynb
├── f4_evaluacion_diferencias.ipynb
└── README.md
```

## Fases del análisis

1. ** Fase 1 - Exploración y limpieza**: detección de nulos, valores atípicos, unión de datasets y ajuste de tipos de datos.
2. ** Fase 2 - Análisis estadístico**: estadísticas descriptivas, correlaciones y distribución de variables categóricas y numéricas.
3. ** Fase 3 - Visualización**: gráficas sobre distribución de vuelos, salarios por educación, tarjetas de fidelidad, etc.
4. ** Fase 4 - Evaluación de diferencias**: análisis de diferencias en vuelos reservados según nivel educativo.


##  Tecnologías

- Python 3
- Pandas
- Matplotlib
- Seaborn
