# herramientasbasicas-figueroa-sofia
# Análisis de Ventas E-Commerce 2023

**Autora:** Sofía Figueroa  
**Curso:** Herramientas Básicas para el Análisis de Datos  

## Objetivo del proyecto

El objetivo de este proyecto es realizar un análisis exploratorio de un dataset ficticio de ventas de comercio electrónico correspondientes al año 2023. El análisis busca identificar cómo se distribuyen las ventas según las categorías de productos, analizar la evolución mensual de la facturación, conocer los medios de pago más utilizados y estudiar la distribución de los pedidos según su estado.

La pregunta principal que guía el análisis es: ¿Cómo se distribuyeron las ventas de un comercio electrónico durante el año 2023 según las categorías de productos, los meses, los medios de pago y el estado de los pedidos?

## Dataset

El dataset utilizado fue **Fictional E-Commerce Sales Data**, obtenido de Kaggle. Se utilizó el archivo `larger_sales_dataset.csv`, que contiene 10.000 registros y 10 variables relacionadas con pedidos, productos, cantidades, precios, fechas, clientes, medios de pago y estados de los pedidos.

Fuente del dataset:  
[https://www.kaggle.com/datasets/hassaneskikri/fictional-e-commerce-sales-data?resource=download]

## Proceso realizado

El proyecto fue desarrollado utilizando Python, pandas, Matplotlib y Seaborn para realizar la carga, limpieza y exploración de los datos. Se revisaron los tipos de datos, valores nulos y registros duplicados. Además, se verificó la consistencia de los precios totales mediante el cálculo de Quantity multiplicado por Unit Price.

Posteriormente, se calcularon los principales indicadores del negocio: ventas totales, cantidad de pedidos, unidades vendidas y ticket promedio.

Los resultados principales se visualizaron mediante gráficos de evolución mensual de ventas, ventas por categoría, pedidos por medio de pago y distribución de los pedidos según su estado.

Finalmente, se desarrolló un dashboard interactivo en Power BI con KPIs, gráficos y filtros que permiten analizar la información de manera dinámica.

## Resultados principales

Las ventas totales alcanzaron 7.627.241,97, con 10.000 pedidos registrados y 30.097 unidades vendidas. El ticket promedio fue de aproximadamente 762,72. La categoría Sports & Outdoors fue la que presentó el mayor nivel de ventas.

## Herramientas utilizadas

- Python
- Pandas
- Matplotlib
- Seaborn
- Power BI
- GitHub

## Archivos del proyecto

- Dataset original: `/data/raw/larger_sales_dataset.csv`
- Notebook de análisis: `/notebooks/analisis_ecommerce_2023.ipynb`
- Dashboard de Power BI: `/dashboard/dashboard_ecommerce_2023.pbix`
- Captura del dashboard: `/dashboard/dashboard_ecommerce.png`
