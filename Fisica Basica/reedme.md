# Configuración de Escena y Cinemática Básica

## Descripción

Este proyecto implementa una escena 3D en WebGL utilizando Three.js, donde se aplican principios básicos de cinemática para simular movimiento rectilíneo uniforme, movimiento rectilíneo uniformemente variado y control de usuario mediante teclado.

## Objetivo

Instanciar un motor gráfico web y programar movimientos matemáticos básicos basados en posición, velocidad y aceleración dentro de un espacio virtual 3D.

## Tecnologías utilizadas

- HTML
- JavaScript
- Three.js
- WebGL

## Sistemas implementados

### MRU - Movimiento Rectilíneo Uniforme

Un cubo rojo se desplaza en línea recta con velocidad constante.

Ecuación aplicada:

x = x0 + vt

### MRUV - Movimiento Rectilíneo Uniformemente Variado

Una esfera azul se mueve con velocidad inicial y aceleración constante simulando gravedad.

Ecuación aplicada:

Δx = v0t + 1/2at²

También se actualiza la velocidad mediante:

v = v0 + at

### Control de usuario

Un cubo verde puede ser controlado con las teclas WASD. Su movimiento utiliza aceleración, velocidad máxima y fricción para lograr una respuesta más fluida.

## Controles

- W: mover hacia adelante
- S: mover hacia atrás
- A: mover a la izquierda
- D: mover a la derecha
- Espacio: reiniciar la esfera MRUV

## Conclusión

La práctica demuestra cómo aplicar ecuaciones básicas de cinemática dentro de un entorno interactivo 3D. Además, se implementó entrada de usuario para mostrar cómo estos principios físicos pueden utilizarse en sistemas reales de movimiento para videojuegos.