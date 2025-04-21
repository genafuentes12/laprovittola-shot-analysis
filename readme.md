# Análisis y Predicción de Tiros de Nicolás Laprovittola

Este proyecto utiliza redes neuronales convolucionales (CNN) con Keras y Random Forest para analizar y predecir el éxito de los tiros de Nicolás Laprovittola durante su última temporada en la Euroliga (2023-2024). 

## Objetivo
- Desarrollar un modelo de aprendizaje profundo para predecir si un tiro será exitoso o no, basándose en variables como la posición en la cancha, el momento del partido y la diferencia de puntos.

## Pasos del Proyecto
1. **Extracción de datos**: Los datos de los tiros fueron obtenidos mediante la API de la Euroliga.
2. **Preprocesamiento**: Se procesaron las coordenadas, identificando tiros encestados y fallados.
3. **Análisis exploratorio**:
   - Mapas de calor y gráficos de dispersión para identificar patrones de tiro.
   - Cálculo de porcentajes de efectividad desde distintas zonas de la cancha.
4. **Implementación del modelo CNN y Random Forest**: 
   - Entrenamiento del modelo para predecir el éxito de un tiro.
   - Evaluación de la precisión mediante métricas como la matriz de confusión.
5. **Visualización**: 
   - Generación de gráficos interactivos y estáticos del rendimiento del jugador.

## Requisitos
Para ejecutar este proyecto, necesitas instalar las siguientes librerías de Python:
- `tensorflow`
- `pandas`
- `matplotlib`
- `scikit-learn`

Instala las dependencias con:
```bash
pip install tensorflow pandas matplotlib scikit-learn
```

## Cómo ejecutar
1. Clona este repositorio:
```bash
git clone https://github.com/tu_usuario/laprovittola-shot-analysis.git
cd laprovittola-shot-analysis
```
2. Abre el archivo laprovittola_shot_analysis.ipynb en Jupyter Notebook o Google Colab.

3. Ejecuta las celdas en orden para reproducir el análisis y las predicciones.

## Resultados
- Mapas de calor y gráficos muestran las zonas de mayor efectividad de Laprovittola.
- El modelo CNN alcanzó una precisión del 59% en la predicción de tiros exitosos.
- El modelo Random Forest alcanzó una precisión del 65%.

## Futuras Mejoras
- Ampliar el análisis a otros jugadores o temporadas.
- Explorar arquitecturas de modelos más avanzadas para mejorar la precisión.
