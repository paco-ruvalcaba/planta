Repositorio para el proyecto del diseño desde cero de una planta de clasificación de piezas utilizando OpenScad.

# Objetivo
Diseñar una planta clasificadora de piezas desde cero utilizando OpenSCAD y su característica de animación.
# Objetivos Particulares
- [ ] Diseñar las piezas necesarias desde cero.
- [ ] Armar con las piezas generadas la planta de clasificación.
- [ ] Generar una animación simple del funcionamiento de la planta de clasificación.
***
# Instrucciones
## 1. Diseño de la pieza "Cube (Cubo)"
En la planta de clasificación se clasificarán dos tipos de piezas. Una de ellas tiene forma de cubo. El cubo tendrá las siguientes características:
- Los lados tendrán 25 mm de longitud.
- Al tratarse de un cubo, todas las caras serán cuadradas y del mismo tamaño.
- El cubo utilizará como sistema de coordenadas de referencia el plano X/Y
## 2. Diseño de la pieza "Cylinder (Cilindro)"
La segunda pieza de la planta de clasificación será un cilindro con las siguientes características:
-  El cilindro tendrá un diámetro de 30 mm y una altura de 10 mm.
-  El centro del círculo de la interfaz está orientado al origen del sistema de coordenadas.
-  Como sistema de coordenadas de referencia se utilizará el plano X/Y.
## 3.  Diseño de la cinta transportadora "ConveyorShort" (cinta corta)
Para transportar las piezas hasta el proceso de clasificación se necesitan cintas transportadoras.Crearemos la primera cinta transportadora, la más corta, denominada "ConveyorShort". Esta cinta transportará las piezas diseñadas hasta el proceso de clasificación. "ConveyorShort" es un sólido con las siguientes propiedades:
- La cinta tiene una longitud de 150 mm, un ancho de 65 mm y una altura de 10 mm.
- Los bordes de ambos extremos de la superficie de transporte están redondeados con un radio de 5 mm
# 4. Diseño de la cinta transportadora "ConveyorLong" 
La segunda cinta transportadora, "ConveyorLong", es necesaria para transferir las piezas hacia el proceso de clasificación. "ConveyorLong" tiene los siguientes parámetros: 
- La cinta tiene una longitud de 390 mm, un ancho de 65 mm y una altura de 10 mm.
- Los bordes de ambos extremos de la superficie de transporte están redondeados con un radio de 5 mm.