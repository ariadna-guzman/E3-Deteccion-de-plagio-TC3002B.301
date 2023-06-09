# Repositorio para las Evidencias del Bloque

## Materia: Desarrollo de Aplicaciones Avanzadas de Ciencias Computacionales TC3002B.301

## Integrantes del Equipo:
* Jorge Chávez Badillo A01749448
* Amy Murakami Tsutsumi A01750185
* Ariadna Jocelyn Guzmán Jiménez A01749373

### Evidencia 1: Análisis de Similitud Empleando Inteligencia Artificial
[Link Google Colab Evidencia 1](https://colab.research.google.com/drive/1t1762-aYlW37PJ9KtEQRkcM4U2q4I8WS?usp=sharing)

#### Solución Propuesta
Mediante esta primera evidencia, se busca poder realizar una detección de plagio comparando un archivo sospechoso con cada uno de los archivos genuinos existentes en la base de datos, para así poder identificar la existencia de cierto grado de similitud entre los archivos para finalmente poder clasificar el archivo como Plagio (1) o Genuino (0).

Para ello, es importante mencionar los siguientes conceptos importantes, ya que son los modelos, algoritmos y métricas implementadas para la implementación:

* stemming: Técnica utilizada en procesamiento de lenguaje natural que consiste en reducir las palabras a su forma base o raíz.
* n-gram: Secuencia continua de n elementos tomados de una muestra de texto.
* cosine similarity: Medida de similitud entre dos vectores en un espacio multidimensional.
* AUC: Área Bajo la Curva. Métrica de rendimiento utilizada en problemas de clasificación.
* ROC: Curva ROC. Representación gráfica del rendimiento de un modelo de


####  Librerías Implementadas:
* nltk: Se utiliza para el procesamiento del lenguaje natural, en caso de esta evidencia para la implementación de stemming y la creación de eneagramas.
* sklearn: Se utiliza para realizar tareas relacionadas con el aprendizaje automático, en este caso la extracción de palabras y el cálculo de la distancia de coseno.
* os: Sirve para realizar la gestión de archivos y el directorio donde se encuentra la base de datos con textos genuinos y sospechosos.|


### Evidencia 2: Modelo Mejorado
[Link Google Colab Evidencia 2](https://colab.research.google.com/drive/1TGzVXwm-qTHs-tEwzlKu4bmfS1Cwi72w?usp=sharing)

#### Solución Propuesta
Dentro de esta segunda evidencia, se implementa una mejora a nuestro sistema de detección de plagio a través de encoders utilizando el transformer BERT (Bidirectional Encoder Representations From Transformers), el cual nos ayuda de mejor manera a la precisión en comparación de textos.

#### Librerías Implementadas:
* sklearn: Se utiliza para realizar tareas relacionadas con el aprendizaje automático, en este caso la extracción de palabras y el cálculo de la distancia de coseno.
* os:  Sirve para realizar la gestión de archivos y el directorio donde se encuentra la base de datos con textos genuinos y sospechosos.
* matplotlib: Para la visualización de las métricas a través de gráficos.
* pandas: Se utiliza para la manipulación de datos a través de DataFrames.
* tqdm: Permite visualizar el progreso de las tareas en tiempo real.
* numpy: Ayuda a la creación de matrices y arreglos para su manipulación y operaciones matemáticas.
* keras_preprocessing: Permite la normalización de datos, codificación de variables categóricas y la división de conjuntos de datos en entrenamiento y prueba. 
* transformers: Se centra en el procesamiento de lenguaje natural, en este caso, es la biblioteca más importante nos brinda el modelo BERT para su implementación.



