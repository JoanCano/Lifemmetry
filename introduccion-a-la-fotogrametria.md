---
description: Conceptos básicos de fotogrametr
---

# Introducción a la fotogrametría

## Qué es la fotogrametría

Definiciones hay muchas.. pero si tuviese que explicarle a alguien qué es la fotogrametría le diría que _es una técnica para obtener modelos tridimesionales con su forma, dimensión y posición, a partir de varias imágenes tomadas del objeto en cuestión. Por lo tanto, estamos obteniendo un objeto con características geométricas y medidas métricas._

La fotogrametría es una tecnología fundamentalmente democrática: puede realizarla cualquier persona con una cámara de teléfono y acceso a un software gratuito de fotogrametría. Sin embargo, para producir el tipo de modelos 3D de alta resolución que capturan con precisión la geometría y el detalle de la superficie de un objeto, se requiere un alto nivel de habilidad tanto para la grabación de datos como para el procesamiento de datos. En general, cuanto mejor sea el sensor de la cámara y la capacidad de resolución de la lente, mejores serán los datos. La habilidad del operador, la calidad y el número de imágenes capturadas y la distancia del sensor de la cámara a la superficie del objeto también juegan un papel importante en la determinación de la resolución y el detalle de los datos 3D.

**¿Qué es la fotogrametría?**

La fotogrametría es el proceso de creación de un activo digital utilizando varias fotos de la imagen original. objeto mundial Hay diferentes usos para la fotogrametría, y el flujo de trabajo puede variar dependiendo de la

contexto.

Este documento tiene como objetivo describir un flujo de trabajo de fotogrametría dedicado a la creación de activos de juegos con Un presupuesto asequible para un estudio de juegos. Si bien es posible crear activos de muy alta calidad para el uso no relacionado con el juego mediante fotogrametría, este documento se enfoca en el uso de la fotogrametría para el juego desarrollo, y por lo tanto describe cómo obtener los mejores resultados dentro del tiempo y presupuesto típicos Restricciones del desarrollo del juego. En la siguiente sección se incluye una selección de equipos y software, que proporcionan un equilibrio entre Eficiencia, coste y calidad.

**La fotogrametría** es la ciencia de hacer mediciones a partir de fotografías. Infiere la geometría de una escena de un conjunto de fotografías o videos no ordenados. La fotografía es la proyección de una escena 3D en un plano 2D, perdiendo información de profundidad. El objetivo de la fotogrametría es revertir este proceso. El modelado denso de la escena es el resultado del encadenamiento de dos tuberías basadas en la visión por computadora: "Estructura desde el movimiento" \(SfM\) y "Estéreo de vista múltiple" \(MVS\).

La fotogrametría también es inherentemente "portátil": en la mayoría de los casos, el equipo \(cámara, trípode, flashes\) puede caber en una pequeña bolsa para la cámara, lo que lo convierte en una herramienta particularmente útil para grabar en sitios remotos o peligrosos.

[https://alicevision.github.io/\#history](https://alicevision.github.io/#history)



### Tipo de fotografías

* En función de su posición
  * Aérea o terrestre
  * Vertical, oblicua, horizontal
* En función del tipo de cámara
  * Métricas \(fotogramas\)
  * No métricas \(fotografías\)
* Tipo se sensor
  * Analógico o digital
  * Matricial, lineal o puntual

Lo más común es que para fotogrametría con un fin cartográfico se utilicen cámaras aéreas, verticales y métricas. Sin embargo, desde que los drones han entrado en el mercado, se está realizando mucha cartografía en base a sus cámaras, por lo que estamos delante de cámaras aéreas, verticales, no métricas, digitales y matriciales.

{% hint style="info" %}
Tener una cámara de matriz lineal o matricial nos puede aportar ventajas y desventajas. Para mi son mejor las matriciales para evitarnos el efecto _rolling shutter_ 
{% endhint %}

![](.gitbook/assets/image%20%281%29.png)



