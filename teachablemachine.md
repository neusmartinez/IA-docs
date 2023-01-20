# INTRODUCCIÓN AL EJERCICIO

Vamos a entrenar un modelo de Teachable Mchine para que sea capaz de identificar a que contenedor tenemos que tirar un residuo.

## PASOS A SEGUIR

1. Elección de clases y datos de entrenamiento.
Vamos a añadir 3 clases de contenedores:
 * Contenedor amarillo
 * Contenedor verde.
 * Contenedor azul.
 
2. Entrenamiento del modelo.
Vamos a añadir 5 imágenes de residuos que se deben tirar a cada uno de los contenedores.

3. Evaluación del modelo y conclusiones despues de hacer tests propios (problemas y soluciones).

## Test 1
INTRODUCCIÓN AL PROBLEMA: Probamos con una fotografía de una botella de spray con pulverizador y nos da una clasificaión de contenedor erronea (verde).
![](https://github.com/neusmartinez/IA-docs/blob/main/Problema%201.png)

SOLUCIÓN: Como solución,cogemos una botella con un elemento común: el pulverizador. Y por suerte, aunque el spray de prueba sea de otro color, lo ha podido reconocer como plástico. Aún así,se debe reentrenar el modelo para que aprenda mejor la diferencia entre los materiales, y no se centre en las formas.
![](https://github.com/neusmartinez/IA-docs/blob/main/Soluci%C3%B3n%201.png.)


## Test 2
INTRODUCCIÓN AL PROBLEMA:Probamos con un rollo de papel y nos da una clasificación de contenedor correcta pero con un porcentaje bajo.La parte buena es que ha reconocido el rollo de papel por los colores y no por la forma. 
![](https://github.com/neusmartinez/IA-docs/blob/main/Problema%202.png)

SOLUCIÓN:Como solución, ponemos rollos parecidos para que detecte la misma forma, pero de otros colores para que no solo se base en el color.
![](https://github.com/neusmartinez/IA-docs/blob/main/Soluci%C3%B3n%202.png)

4. Evaluación del modelo y conclusiones despues de hacer de imágenes de Aules (problemas y soluciones).
