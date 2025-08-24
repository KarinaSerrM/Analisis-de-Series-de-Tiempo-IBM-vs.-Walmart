# Análisis de Series Temporales: IBM vs Walmart

Este proyecto presenta un análisis completo de las series temporales de precios de las acciones de IBM y Walmart durante los últimos 5 años, con enfoque en la diversificación de portafolios, comportamiento estacional y predicción de precios.

## Objetivos del análisis

- Evaluar la correlación entre los rendimientos de IBM y Walmart para identificar oportunidades de diversificación.
- Descomponer las series temporales en componentes de tendencia, estacionalidad y residuos.
- Aplicar pruebas de estacionariedad (Dickey-Fuller) para validar la naturaleza de las series.
- Analizar la autocorrelación de precios y rendimientos.
- Realizar predicciones con medias móviles y evaluar su precisión con RMSE y MAPE.

## Metodología

1. **Obtención de datos históricos** desde Yahoo Finance.
2. **Visualización inicial** de precios de cierre.
3. **Cálculo de rendimientos diarios** y análisis de correlación.
4. **Descomposición estacional** con `statsmodels`.
5. **Prueba de Dickey-Fuller** para evaluar estacionariedad.
6. **Autocorrelación** con gráficos ACF.
7. **Predicción con medias móviles** (20, 50 y 200 días).
8. **Evaluación de precisión** con métricas cuantitativas.

## Resultados clave

- Correlación de rendimientos: **0.30**, lo que sugiere baja dependencia y alta utilidad para diversificación.
- Ambas series muestran **tendencia positiva** y comportamiento estacional.
- Los **rendimientos son estacionarios**, los **precios no**.
- El modelo de predicción de Walmart mostró **mayor precisión** (MAPE: 2.98%) frente a IBM (MAPE: 5.06%).

## Tecnologías utilizadas

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Statsmodels
- Scikit-learn
- Yahoo Finance API

## Conclusión

Este análisis demuestra cómo la estadística aplicada y la visualización estratégica pueden apoyar decisiones de inversión más informadas. La baja correlación entre IBM y Walmart refuerza el valor de la diversificación, mientras que los modelos de predicción permiten anticipar movimientos con base en patrones históricos.
  
 (https://www.linkedin.com/in/karina-serrano-data-science/)!
