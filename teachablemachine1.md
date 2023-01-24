# INTRODUCCIÓN AL EJERCICIO

Voy a entrenar un modelo de Teachable Mchine para que sea capaz de identificar a que contenedor tenemos que tirar un residuo.

## PASOS A SEGUIR

1. Elección de clases y datos de entrenamiento.
Voy a añadir 3 clases de contenedores:
 * Contenedor amarillo
 * Contenedor verde.
 * Contenedor azul.
 
2. Entrenamiento del modelo.
Voy a añadir 5 imágenes de residuos que se deben tirar a cada uno de los contenedores.

3. Evaluación del modelo y conclusiones despues de hacer tests propios (problemas y soluciones).

## SIN PROBLEMAS:
* Botella de vidrio marrón:

![](https://github.com/neusmartinez/IA-docs/blob/main/BOTELLA%20VIDRIO%20MARRO%CC%81N.png)

* Bote de cristal:

![](https://github.com/neusmartinez/IA-docs/blob/main/BOTE%20DE%20CRISTAL.png)

* Botella de vidrio verde:

![](https://github.com/neusmartinez/IA-docs/blob/main/BOTELLA%20VERDE.png)

* Restos de comida 1:

![](https://github.com/neusmartinez/IA-docs/blob/main/RESTOS%201.png)

* Restos de comida 2:

![](https://github.com/neusmartinez/IA-docs/blob/main/RESTOS%202.png)

* Pañal:

![](https://github.com/neusmartinez/IA-docs/blob/main/PAN%CC%83AL.png)


* Tapón de corcho:

![](https://github.com/neusmartinez/IA-docs/blob/main/TAPO%CC%81N%20DE%20CORCHO.png)

* Tubo de cartón:

![](https://github.com/neusmartinez/IA-docs/blob/main/ROLLO%20DE%20CARTO%CC%81N.png)

* Periódicos: 

![](https://github.com/neusmartinez/IA-docs/blob/main/PERIO%CC%81DICOS.png)

* Brick de cartón:

![](https://github.com/neusmartinez/IA-docs/blob/main/BRICK.png)

* Lata CocaCola:

![](https://github.com/neusmartinez/IA-docs/blob/main/LATA%20%20COCACOLA.png)

* Lata normal:

![](https://github.com/neusmartinez/IA-docs/blob/main/LATA%20NORMAL.png)

* Bote de plástico con dosificador:

![](https://github.com/neusmartinez/IA-docs/blob/main/CHUFCHUF.png)

## PROBLEMAS:
* Huevera: Lo reconoce como un residuo que se debe tirar en el contenedor gris (erróneo).

![](https://github.com/neusmartinez/IA-docs/blob/main/PROBLEMA%20HUEVERA.png)

* Bola de aluminio: Lo reconoce como un residuo que se debe tirar en el contenedor marrón (erróneo).

![](https://github.com/neusmartinez/IA-docs/blob/main/PROBLEMA%20BOLA%20ALUMINIO.png)

## SOLUCIONES A LOS PROBLEMAS:
* Huevera: Añado imagenes de conjuntos de hueveras aunque de diferente color. Tras esto, ya lo reconoce como un residuo que se debe depositar en el contenedor azul y no el contenedor gris.

![](https://github.com/neusmartinez/IA-docs/blob/main/SOLUCIO%CC%81N%20HUEVERA.png)

* Bola de aluminio: Añado imágenes de aluminio para que reconozca el color. Tras esto, ya lo reconoce como un residuo que se debe depositar en el contenedor amarillo y no en el contenedor marrón.

![](https://github.com/neusmartinez/IA-docs/blob/main/SOLUCIO%CC%81N%20BOLA%20ALUMINIO.png)

4. Realizo una ultima comprobación de todos los residuos y sale todo correcto, cada residuo en su correspondiente contenedor.
