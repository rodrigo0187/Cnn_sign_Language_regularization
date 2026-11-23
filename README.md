# Cnn_sign_Language_regularization

## Descripción del proyecto

Este proyecto consiste en el desarrollo, optimización y evaluación de modelos de Deep Learning para la clasificación de imágenes de señas.

El objetivo es desarrollar un modelo capaz de reconocer diferentes señas del alfabeto americano a partir de imágenes de manos. 

Se implementan y comparan 2 arquitecturas de Deep Learning, un Perceptrón multicapa (MLP) y una Red Convolucional (CNN), incorporando técnicas de regularización y herramientas de evaluación de desempeño y capacidad de generalización.

## Dataset

Se utiliza el dataset Sign Language MNIST, compuesto por imágenes de 28 x 28 píxeles en escala de grises, que corresponden a diferentes señas del ASL.

## Tecnologías utilizadas
- Python
- TensorFlow/Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-Learn
- Visualkeras
- Google Colab

## Estructura del proyecto

```text
Cnn_sign_Language_regularization/
├── dataReal/
│   └── # Imágenes externas para pruebas
├── img/
│   └── # Imágenes de manos realizando el alfabeto del ASL
├── model/
│   ├── modelo_cnn.keras
│   └── red_baseline_mlp.keras
├── notebooks/
│   └── cnn_regularization.ipynb
└── README.md
```

## Integrantes:
- Rodrigo Aedo
- Benjamin Figueroa
- Martina López
