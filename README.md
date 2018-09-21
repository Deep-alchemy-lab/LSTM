# LSTM

a. Introduction

El LSTM es un tipo de Recurrent Neural Network. 

Los RNN son capaces de conectar informacion previa a la tarea actual. Tiene serias problematicas 
a medida que crecen los gaps, que evitan que el algoritmo conecte la informacion pasada. 

El LSTM logra solucionar esta problematica. El LSTM es capaz de aprender dependencias de largo plazo, recordando informacion por
plazos de tiempo muy largos. El LSTM tiene una estructura en cadena con 4 layer de cadenas de neuronas que interactuan. Adicionalmente, tiene una puerta de entrada y salida a la celula de informacion. 

En el siguiente link se puede obtener una explicacion simplificada del LSTM: 
http://colah.github.io/posts/2015-08-Understanding-LSTMs/

Es importante aclara que existen multiples versiones del LSTM, en los siguientes papers se incluyen las multiples versiones: 

An Empirical Exploration of Recurrent Network Architectures:
http://proceedings.mlr.press/v37/jozefowicz15.pdf
LSTM: A Search Space Odyssey:
https://arxiv.org/pdf/1503.0469.pdf

En general todas las variantes son similares, aun asi, hay LSTM's que funcionan mejor en ciertas tareas que otros.  

LSTM basic code (Explained)

Table of Content:

1. Layers used to build an LSTM

  1.1
  1.2
  1.3

2. Architecture

3.
Anexo. 
