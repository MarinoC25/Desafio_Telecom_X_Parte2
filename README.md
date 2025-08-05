# Desafio_Telecom_X_Parte2
El presente informe documenta el análisis predictivo realizado para identificar los clientes con mayor probabilidad de evasión (churn) en una empresa de telecomunicaciones. Se empleó un modelo de Random Forest con umbral ajustado, lo que permitió mejorar la detección de clientes en riesgo y proponer estrategias efectivas de retención
Una vez que el modelo de predicción de evasión de clientes (churn) alcanza un desempeño satisfactorio, es necesario guardar el modelo entrenado para su reutilización en entornos productivos o posteriores análisis sin necesidad de reentrenarlo.

Este proceso permite:

Reducir tiempos de ejecución.

Garantizar reproducibilidad de resultados.

Facilitar la integración del modelo en aplicaciones externas.

Versionar los modelos entrenados para comparar mejoras futuras.

En Python, este procedimiento se realiza mediante librerías como pickle o joblib. La segunda es recomendada por su eficiencia para objetos de gran tamaño, como los modelos de machine learning.

Procedimiento

Después de entrenar el modelo de Random Forest y ajustar el umbral de clasificación (0.35 en este caso), se procede a su almacenamiento. El archivo generado podrá ser cargado nuevamente en Google Colab o en cualquier entorno de Python compatible.
