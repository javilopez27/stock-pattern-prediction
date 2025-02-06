# LSTM with Attention - Advanced

## Descripción del Proyecto

Este cuaderno implementa una arquitectura LSTM con mecanismos de atención avanzada. El objetivo es mejorar la capacidad de los modelos LSTM para capturar dependencias a largo plazo en secuencias de datos, aplicando mecanismos de atención que permiten ponderar la importancia de diferentes elementos de entrada.

Este trabajo fue inspirado por un artículo que leí del Dr. Ernesto Lee sobre modelos LSTM con atención.

## Requisitos Previos

Para ejecutar este cuaderno, es necesario instalar las siguientes dependencias:

```bash
pip install tensorflow keras yfinance numpy pandas matplotlib scikit-learn
```

También se recomienda tener un entorno de Python 3.x y Jupyter Notebook instalado.

## Estructura del Proyecto

El cuaderno contiene las siguientes secciones:

- Introducción al modelo LSTM con atención.
- Preprocesamiento de datos y normalización.
- Implementación de la arquitectura del modelo.
- Entrenamiento y evaluación.
- Visualización de resultados.

## Uso

Para ejecutar el cuaderno, sigue estos pasos:

1. Descarga o clona este repositorio.
2. Abre el cuaderno en Jupyter Notebook o Google Colab.
3. Ejecuta las celdas en orden para entrenar y evaluar el modelo.

## Explicación de las Funcionalidades

El cuaderno realiza los siguientes procesos clave:

- **Carga de datos**: Obtención de datos financieros mediante `yfinance`.
- **Preprocesamiento**: Normalización de datos usando `MinMaxScaler`.
- **Implementación del modelo**: Definición de una red LSTM con mecanismos de atención.
- **Entrenamiento del modelo**: Ajuste de parámetros mediante `TensorFlow` y `Keras`.
- **Evaluación**: Visualización de la predicción del modelo.

## Configuración y Parámetros

El cuaderno permite configurar diversos parámetros, como:

- Número de capas y neuronas en la LSTM.
- Tamaño del conjunto de entrenamiento y validación.
- Número de épocas y tamaño del batch.

## Consideraciones y Limitaciones

- Los resultados pueden variar según el conjunto de datos utilizado.
- Se recomienda ajustar los hiperparámetros para mejorar la precisión.
- El rendimiento del modelo depende del poder computacional disponible.

## Contribuciones

Si deseas contribuir a este proyecto:

1. Realiza un fork del repositorio.
2. Crea una rama con tu mejora (`git checkout -b mejora`).
3. Haz commit de los cambios (`git commit -m "Descripción de la mejora"`).
4. Envía un pull request.

## Licencia

Este proyecto se distribuye bajo la licencia MIT. Puedes usarlo libremente con fines educativos y de investigación.

