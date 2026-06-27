# AA - Aprendizaje Automático

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-orange)
![scikit-learn](https://img.shields.io/badge/ML-scikit--learn-green)
![TensorFlow](https://img.shields.io/badge/Deep%20Learning-TensorFlow-red)
![Reinforcement Learning](https://img.shields.io/badge/RL-Q--Learning-purple)

Repositorio de prácticas de la asignatura **Aprendizaje Automático**.

El proyecto reúne trabajos desarrollados en notebooks de Jupyter/Google Colab sobre aprendizaje supervisado, aprendizaje no supervisado, Deep Learning y aprendizaje por refuerzo.

---

## Resultados académicos

| Trabajo | Contenido principal | Calificación |
|---|---|---:|
| P1 | Aprendizaje supervisado: clasificación y regresión | 5,8/10 |
| P2 | Aprendizaje no supervisado: clustering y reglas de asociación | 9,63/10 |
| P3 | Deep Learning: clasificación de imágenes y autoencoders | 10/10 |
| Proyecto grupal | Aprendizaje por refuerzo con Gymnasium y Q-Learning | 9,8/10 |

---

## Tecnologías utilizadas

- Python
- Jupyter Notebook / Google Colab
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- TensorFlow / Keras
- mlxtend
- Gymnasium

---

## Estructura del repositorio

```text
AA/
├── P1_JOAQUIN_CRUZ_LORENZO.ipynb
├── P2_JOAQUIN_CRUZ_LORENZO.ipynb
├── P3_JOAQUIN_CRUZ_LORENZO.ipynb
├── Proyecto.ipynb
└── README.md
```

---

## P1 - Aprendizaje supervisado

**Calificación:** 5,8/10

La primera práctica trabaja problemas de **aprendizaje supervisado**.

### Ejercicio 1: Clasificación

Problema de clasificación aplicado a datos de sensores. Se realiza análisis exploratorio, preprocesado, estudio de correlaciones, tratamiento de valores faltantes, gestión de outliers, escalado y validación de modelos.

**Modelos utilizados:**

- Regresión Logística.
- Random Forest.
- SVC.

### Ejercicio 2: Regresión

Problema de regresión aplicado a datos de sensores para predecir una variable continua.

**Modelos utilizados:**

- Regresión lineal.
- SVR.
- Random Forest Regressor.

---

## P2 - Aprendizaje no supervisado

**Calificación:** 9,63/10

La segunda práctica se centra en técnicas de **aprendizaje no supervisado**.

### Ejercicio 1: Clustering

Aplicación de técnicas de agrupamiento sobre el conjunto de datos **Old Faithful**.

**Algoritmos utilizados:**

- K-Means.
- DBSCAN.
- k-NN como apoyo para asignar nuevos puntos.

### Ejercicio 2: Reglas de asociación

Extracción de patrones frecuentes y reglas de asociación en un conjunto de datos de ventas.

**Algoritmos utilizados:**

- Apriori.
- FP-Growth.

**Métricas trabajadas:**

- Soporte.
- Confianza.
- Lift.
- Tiempo de ejecución.

---

## P3 - Introducción a Deep Learning

**Calificación:** 10/10

La tercera práctica introduce técnicas de **Deep Learning** aplicadas a visión por computador e IA generativa.

### Ejercicio 1: Clasificación de imágenes

Clasificación multiclase con **Fashion-MNIST**, usando imágenes en escala de grises de prendas de ropa.

**Modelos trabajados:**

- Red neuronal densa.
- Red neuronal convolucional.

### Ejercicio 2: Autoencoders

Construcción de un **autoencoder** sobre MNIST para reconstrucción y generación de imágenes a partir de un espacio latente.

**Aspectos trabajados:**

- Encoder.
- Decoder.
- Autoencoder completo.
- Evaluación de reconstrucción.
- Análisis del espacio latente.
- Generación de nuevas imágenes.

---

## Proyecto grupal - Aprendizaje por refuerzo

**Calificación:** 9,8/10

Proyecto práctico sobre **aprendizaje por refuerzo** con la biblioteca **Gymnasium**.

### Entorno utilizado

- `CliffWalking-v0`

### Contenidos principales

- Introducción al aprendizaje por refuerzo.
- Agente, entorno, estado, acción y recompensa.
- Definición y comparación de políticas.
- Evaluación de política aleatoria y política manual.
- Implementación de Q-Learning.
- Selección de hiperparámetros.
- Análisis del comportamiento aprendido.

### Autores del proyecto

- Joaquín Cruz Lorenzo.
- José Gómez Moreno-Torres.

---

## Ejecución

Clonar el repositorio:

```bash
git clone https://github.com/juakincruzz/AA.git
cd AA
```

Instalar dependencias habituales:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn tensorflow mlxtend gymnasium notebook
```

Abrir Jupyter Notebook:

```bash
jupyter notebook
```

También pueden ejecutarse directamente en **Google Colab**.

---

## Aprendizajes principales

Este repositorio resume una visión amplia del aprendizaje automático:

- Clasificación y regresión supervisada.
- Clustering y reglas de asociación.
- Redes neuronales profundas.
- Redes convolucionales.
- Autoencoders.
- Aprendizaje por refuerzo clásico.
- Evaluación experimental y discusión de resultados.

---

## Autor

**Joaquín Cruz Lorenzo**  
GitHub: [@juakincruzz](https://github.com/juakincruzz)
