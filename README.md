EverPeak Retail Analytics

Descripción del Proyecto

Este proyecto analiza datos transaccionales de EverPeak con el objetivo de comprender el comportamiento de compra de los clientes, identificar valores atípicos (outliers) y desarrollar segmentos de negocio que permitan mejorar las estrategias de marketing, inventario y finanzas.

A través de técnicas de análisis exploratorio de datos (EDA), se estudian variables como edad de clientes, cantidad de productos comprados, valor de las órdenes y métodos de pago para generar insights accionables para la toma de decisiones.

Objetivos de Negocio:

Analizar la distribución de compras realizadas por los clientes.
Detectar valores atípicos que puedan afectar los indicadores del negocio.
Comparar diferentes métodos estadísticos para identificar outliers.
Segmentar clientes según volumen de compra.
Clasificar transacciones de acuerdo con el método de pago utilizado.
Generar información útil para estrategias comerciales y de marketing.

El proyecto utiliza los datasets:

everpeak_clean.csv
everpeak_retail.csv

Hallazgos Principales

La distribución de compras presenta asimetría positiva (sesgo a la derecha).
Un grupo reducido de clientes realiza compras significativamente mayores que el promedio.
La mediana representa mejor al cliente típico que la media.
Los métodos IQR y Z-Score identifican diferentes cantidades de outliers dependiendo de la distribución de los datos.
Existen oportunidades para desarrollar estrategias diferenciadas para clientes de alto volumen.

Tecnologías Utilizadas:

Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook
