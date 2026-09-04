# Trabajo Final Integrador – Herramientas Básicas para el Análisis de Datos

**Autor:** Sofía Figueroa  
**Curso:** Herramientas Básicas para el Análisis de Datos  
**Cohorte:** Comisión 2026

## 📊 Objetivo del proyecto

El objetivo de este proyecto es realizar un análisis exploratorio de datos sobre las ventas de un comercio electrónico durante el año 2023. Para ello, se integraron las herramientas Python, Power BI y GitHub, desarrollando un flujo completo de análisis desde la selección del dataset hasta la visualización y publicación de los resultados.

La pregunta principal del análisis fue:

**¿Cómo se comportaron las ventas del e-commerce durante el año 2023 y qué categorías, medios de pago y estados de pedido se destacan en los resultados?**

A partir de esta pregunta se analizaron las ventas mensuales, el desempeño de las categorías de productos, los medios de pago utilizados y la distribución de los pedidos según su estado.

## 📁 Dataset

El dataset utilizado es **Fictional E-Commerce Sales Data**, disponible en Kaggle.

Contiene **10.000 registros y 10 variables**, incluyendo información sobre pedidos, productos, categorías, cantidades, precios, fechas, clientes, medios de pago y estados de los pedidos.

**Fuente del dataset:**  
https://www.kaggle.com/datasets/hassaneskikri/fictional-e-commerce-sales-data

El archivo utilizado en este proyecto es:

`larger_sales_dataset.csv`

## 🧹 Proceso de análisis

El análisis fue realizado utilizando Python y las librerías Pandas, Matplotlib y Seaborn.

Las principales etapas fueron:

- Carga y exploración inicial del dataset.
- Revisión de tipos de datos.
- Análisis de valores nulos.
- Identificación de registros duplicados.
- Conversión de la columna de fechas al formato datetime.
- Verificación de consistencia entre Quantity, Unit Price y Total Price.
- Análisis de categorías, medios de pago y estados de pedidos.
- Cálculo de indicadores clave y creación de visualizaciones.

Los principales KPIs obtenidos fueron:

- **Ventas totales:** $7.627.241,97
- **Cantidad de pedidos:** 10.000
- **Ticket promedio:** $762,72
- **Unidades vendidas:** 30.097

## 📈 Dashboard en Power BI

Se desarrolló un dashboard interactivo en Power BI para visualizar los principales resultados del análisis.

El dashboard incluye:

- KPIs de ventas, pedidos y unidades vendidas.
- Evolución mensual de las ventas.
- Ventas por categoría de productos.
- Pedidos según su estado.
- Pedidos según medio de pago.
- Distribución de pedidos por categoría.
- Filtros interactivos por categoría, medio de pago y estado.

## 🛠️ Herramientas utilizadas

- Python
- Pandas
- Matplotlib
- Seaborn
- Power BI
- GitHub

## 📂 Estructura del repositorio

```text
data/raw/
├── larger_sales_dataset.csv

notebooks/
├── Trabajo_Final_Integrador.ipynb

dashboard/
├── dashboard.png
└── dashboardinteractivo_ecommerce.pbix

README.md
