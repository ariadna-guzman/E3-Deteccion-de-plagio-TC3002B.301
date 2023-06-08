# Repositorio para las Evidencias del Bloque

## Materia: Desarrollo de Aplicaciones Avanzadas de Ciencias Computacionales TC3002B.301

## Integrantes del Equipo:
* Jorge Chávez Badillo A01749448
* Amy Murakami Tsutsumi A01750185
* Ariadna Jocelyn Guzmán Jiménez A01749373

### Evidencia 1: Análisis de Similitud Empleando Inteligencia Artificial
#### Solución propuesta

Mediante esta primera evidencia, se busca poder realizar una detección de plagio comparando un archivo sospechoso con cada uno de los archivos genuinos existentes en la base de datos, para así poder identificar la existencia de cierto grado de similitud entre los archivos para finalmente poder clasificar el archivo como Plagio (0) o Genuino (1).

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

[Link Google Colab Evidencia 1](https://colab.research.google.com/drive/1t1762-aYlW37PJ9KtEQRkcM4U2q4I8WS?usp=sharing)

### Evidencia 2: Modelo Mejorado
#### Descripción:
Programa capaz de detectar el plagio de documentos a partir de la implementación de BERT con la librería transformers. 

[Link Google Colab Evidencia 2](https://colab.research.google.com/drive/1TGzVXwm-qTHs-tEwzlKu4bmfS1Cwi72w?usp=sharing)

