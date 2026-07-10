# Analisis_ConnectaTel
Este repositorio contiene el análisis realizado durante el Sprint 7 del caso ConnectaTel.

El dataset `plans` incluye 2 tipos de planes,  `users` incluye 4000 usuarios y `usage` incluye 40000 registros con valores faltantes, sentinels, outliers y problemas de calidad diseñados para simular datos reales del retail. 

**Contenido del repositorio**
notebooks/analisis_ConnectaTel.ipynb → Notebook principal con limpieza e identificación de problemas de calidad de datos , EDA, distribuciones, visualizaciones de distribuciones, identificación de outliers, segmentacion de clientes y conclusiones.

**Cómo reproducir el análisis**
Abre notebooks/everpeak_analysis.ipynb
Ejecuta las celdas en orden
El notebook carga automáticamente el dataset desde /data/ o desde un enlace público (según corresponda)

**Objetivo del análisis**
Identificar problemas de calidad de datos
Identificar patrones de consumo
Diseñar estrategias de retención
Construir un pipeline de limpieza reproducible
Analizar comportamientos, distribuciones y outliers
Sugerir mejoras en los planes
