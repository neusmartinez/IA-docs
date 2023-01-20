# Introducción al problema

Vamos a entrenar un modelo de Teachable Mchine para que sea capaz de identificar a que contenedor tenemos que tirar un residuo.

## Iteración 1

1. Elección de clases y datos de entrenamiento.

Vamos a añadir 3 clases:
 * Contenedor amarillo
 * Contenedor verde.
 * Contenedor azul.
 
2. Entrenamiento del modelo.
Vamos a añadir 5 imágenes de residuos que se deben tirar a cada uno de los contenedores.

3. Evaluación del modelo y conclusiones.

## Test 1
Probamos con una fotografía de una botella de spray con pulverizador y nos da una clasificaión de contenedor erronea (verde).
![](https://github.com/neusmartinez/IA-docs/blob/main/Problema%201.png)

Como solución, hacemos cogemos una botella con un elemento común: el pulverizador. Y por suerte, aunque el spray de prueba sea de otro color, lo ha podido reconocer como plástico. Aún así,se debe reentrenar el modelo para que aprenda mejor la diferencia entre los materiales, y no se centre en las formas.
![](https://github.com/neusmartinez/IA-docs/blob/main/Soluci%C3%B3n%201.png.)


## Test 2
Probamos con un rollo de papel y nos da una clasificación de contenedor errónea (amarillo).
![](https://github.com/neusmartinez/IA-docs/blob/main/Problema%202.png)


## Iteración 2
Mejora de los datos de entrenamiento (opción 1).
Mejora de los parámetros de entremiento (opcion 2).
Evaluación del modelo y conclusiones.
