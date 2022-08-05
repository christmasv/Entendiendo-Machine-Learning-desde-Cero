

# Entendiendo-Machine-Learning-desde-Cero


![Banner](/assets/MLDiagram.png)

Este es un espacio dedicado al entendimiento del Machine Learning desde cero.  Esta guía servirá como introducción a los conceptos básicos de la API de Keras & TensorFlow.  Presentada en notebooks que los puedes ejecutar con: 🗒 [Google Colab](https://colab.sandbox.google.com/).

### 📚 En esta guía, aprendemos sobre:

* -> Introducción Redes Neuronales `CNN` y `RNN`
* -> Tensores, variables y gradientes en TensorFlow.
* -> Creación de capas subclasificando la clase Layer.
- -> Escribir bucles de entrenamiento de bajo nivel.
- -> Seguimiento de las pérdidas creadas por las capas a través del método add_loss()
- -> Seguimiento de las métricas en un bucle de entrenamiento de bajo nivel
- -> Acelerar la ejecución con untf.function
- -> Ejecución de capas en modo de entrenamiento o inferencia
- -> La API funcional de Keras
- -> También verás la API de Keras en acción en dos ejemplos de investigación de extremo a extremo: un Autocodificador Variacional y una Hypernetwork.


## Tensores
TensorFlow es una capa de infraestructura para una programación diferenciable. En esencia, es un marco para manipular matrices N-dimensionales (tensores), al igual que NumPy.

Sin embargo, hay tres diferencias clave entre NumPy y TensorFlow:

TensorFlow puede aprovechar aceleradores de hardware como GPU y TPU.
TensorFlow puede calcular automáticamente el gradiente de expresiones tensor diferenciables arbitrarias.
El cálculo de TensorFlow se puede distribuir a un gran número de dispositivos en una sola máquina y a un gran número de máquinas (potencialmente con varios dispositivos cada una).

## Comparación | Tensorflow - Keras - Pytorch

### Google Tendencias de búsquedas últimos [5 Años ] ←
![tensorflow keras pytorch 5y](https://user-images.githubusercontent.com/5433084/183048006-fa6fbf61-c336-4d77-a701-38ffbd304c60.gif)

### Google Tendencias de búsquedas últimos [12 Mes ] ←
![tensorflow keras pytorch last 12mth](https://user-images.githubusercontent.com/5433084/183051933-10c1f518-34cd-4f18-9eb8-dab2718ad871.gif)

