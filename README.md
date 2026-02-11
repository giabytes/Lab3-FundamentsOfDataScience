# TechLogistics S.A. - Analítica Multidimensional
Maestría en Ciencia de los Datos - Universidad EAFIT

Este proyecto aplica la metodología CRISP-DM para resolver problemas de visibilidad y optimización en una red de sensores de telemetría (energía y agro) en el Oriente Antioqueño.

## Objetivos del Proyecto
Series de Tiempo: Análisis de estacionariedad (ADF) y modelado predictivo de demanda eléctrica.

Procesamiento de Señales: Limpieza de ruido en sensores mediante Transformada de Fourier (FFT) y filtros Butterworth.

Análisis de Grafos: Identificación de nodos críticos ("Cuellos de Botella") en la red de comunicación.

Geo-Inteligencia: Correlación espacial entre biomasa (NDVI), topografía y variables climáticas.

## Stack Tecnológico
Análisis: pandas, numpy, statsmodels.

Señales & Grafos: scipy, networkx.

Visualización: plotly, matplotlib.

## Resultados Clave
Nodo Crítico: Se identificó al Nodo 106 como el punto con mayor Betweenness Centrality (vulnerabilidad sistémica).

Causalidad: El factor de potencia precede al voltaje con un lag de 3, permitiendo alertas tempranas.

Filtrado: Reducción de ruido en sensores con un RMSE de 1.62.

Modelo: Ajuste de modelo ARIMAX (AIC: 8764.57) integrando métricas de red.
