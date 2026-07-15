# Análisis Exploratorio de Datos - Modelo Comercial de Celulares

**Estudiante:** Anthony Isaac Mendoza Palomino  
**Módulo:** Friendly SQL & Python para Analytics  
**Institución:** DMC Institute  

---

## Descripción del dataset

El dataset corresponde a un modelo comercial de ventas de celulares compuesto por 8 tablas relacionadas:

- **Ventas:** tabla principal con 1,499 registros de facturas de venta (2014-2020)
- **País:** catálogo de países donde opera la empresa
- **Cliente:** catálogo de clientes corporativos
- **Vendedor:** catálogo de vendedores
- **Operador:** catálogo de operadores móviles
- **Marca:** catálogo de marcas de celulares (LG, Nokia, Samsung, Apple, Huawei, Motorola)
- **Tienda:** catálogo de tiendas distribuidoras
- **Modelo:** catálogo de modelos de celulares con costos y precios

## Objetivo del análisis

Desarrollar un análisis exploratorio completo que permita identificar tendencias de ventas, evaluar el desempeño de vendedores y mercados, analizar la rentabilidad por producto y detectar problemas de cobranza, para apoyar la toma de decisiones del área comercial.

## Fuente del dataset

Dataset propio generado para el proyecto integrador del Diploma Data Analyst de DMC Institute.

## Principales etapas realizadas

1. **Carga del dataset:** lectura de las 8 hojas del archivo Excel con pandas
2. **EDA:** exploración de dimensiones, tipos de datos, valores nulos y duplicados
3. **Estadística descriptiva:** análisis de variables numéricas y categóricas
4. **Visualizaciones:** 6 gráficos interactivos con Plotly (líneas, barras, pastel, boxplot, histograma, scatter)
5. **Consultas SQL:** 6 consultas con DuckDB incluyendo SELECT, WHERE, GROUP BY, ORDER BY y JOIN

## Tecnologías utilizadas

- Python 3
- pandas
- numpy
- duckdb
- plotly
- Google Colab
- GitHub

## Instrucciones para ejecutar el notebook

1. Sube el archivo `ModeloComercial.xlsx` y el notebook `notebook_analisis_sql_python.ipynb` a Google Colab
2. Abre el notebook en Google Colab
3. Ejecuta la primera celda para instalar las dependencias
4. Ejecuta las celdas en orden de arriba hacia abajo

## Estructura del repositorio

```
├── notebook_analisis_sql_python.ipynb
├── ModeloComercial.xlsx
└── README.md
```
