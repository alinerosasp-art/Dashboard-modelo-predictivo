# Dashboard de análisis predictivo de producción y tiempos muertos

## Descripción

Proyecto de análisis de datos desarrollado como parte del Trabajo Fin de Máster, orientado al análisis de producción y tiempos muertos en un proceso de manufactura cerámica.

La solución integra preparación e integración de datos, análisis exploratorio, modelado predictivo mediante Random Forest y visualización interactiva en Power BI.

## Objetivo

Diseñar e implementar una solución analítica capaz de integrar información histórica de producción y tiempos de paro, identificar patrones operativos y clasificar situaciones asociadas con niveles elevados de paro.

## Tecnologías

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Power BI

## Modelo predictivo

Se implementó un modelo Random Forest para clasificar situaciones asociadas con niveles elevados de paro.

El modelo obtuvo un ROC-AUC de 0.8701. Debido al desbalance de clases, se evaluaron diferentes umbrales de clasificación y se seleccionó un umbral de 0.2395.

## Dashboard

El dashboard desarrollado en Power BI permite analizar:

- Producción.
- M2 buenos y malos.
- Horas de paro.
- Número de paros.
- Nivel de paro.
- Probabilidad de paro alto.
- Predicciones del modelo.
- Análisis por máquina, área y turno.

## Datos

Los datasets originales utilizados en el proyecto no se incluyen en este repositorio debido a restricciones de confidencialidad.

El notebook contiene el código utilizado para la carga, limpieza, transformación e integración de los datos.

## Estructura del repositorio

```text
Dashboard-modelo-predictivo/
│
├── notebooks/
│   ├── Análisis predictivo de producción y tiempos muertos E4.ipynb
│   └── README.md
│
├── dashboard/
│   ├── Dashboard predictivo de producción y tiempos muertos.pbix
│   └── README.md
│
├── datos/
│   └── README.md
│
└── README.md
