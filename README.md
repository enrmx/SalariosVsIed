# Análisis Económico: Salarios e IED en México

Análisis de datos de salarios y fuerza laboral vs Inversión Extranjera Directa en CDMX, Jalisco y Nuevo León (2010-2025).

## Datos

- **Salarios**: Información trimestral de salarios mensuales y fuerza laboral
- **IED**: Inversión Extranjera Directa anual por estado (1999-2024)
- **Estados**: Ciudad de México, Jalisco, Nuevo León

## Estructura

```
datamx/
├── salarios/
│   ├── salario_cdmx.csv
│   ├── salario_jalisco.csv
│   └── salario_nl.csv
├── ied/
│   ├── ied_cdmx.csv
│   ├── ied_jalisco.csv
│   └── ied_nl.csv
├── analisis_economico_mx.ipynb
└── requirements.txt
```

## Instalación

```bash
pip install -r requirements.txt
```

## Uso

```bash
jupyter notebook analisis_economico_mx.ipynb
```

## Análisis Incluidos

1. Carga y preparación de datos
2. Exploración estadística descriptiva
3. Evolución temporal de salarios
4. Análisis de fuerza laboral
5. Tendencias de IED por estado
6. Correlación salarios-IED
7. Análisis de crecimiento
8. Modelo predictivo (Regresión Lineal)
9. Dashboard comparativo interactivo
10. Conclusiones y resumen ejecutivo

## Visualizaciones

- Gráficos de línea temporal
- Gráficos de barras comparativos
- Scatter plots de correlación
- Dashboards interactivos con Plotly
- Análisis de regresión

## Tecnologías

- Python 3.8+
- Pandas, NumPy
- Matplotlib, Seaborn, Plotly
- Scikit-learn
- Jupyter Notebook
