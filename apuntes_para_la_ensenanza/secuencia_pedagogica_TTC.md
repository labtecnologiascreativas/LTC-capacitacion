# Aproximación pedagógica para las actividades de LTC

## Taller de Tecnologías Creativas

Las actividades del Taller de Tecnologías Creativas están organizadas en "Desafíos". Cada carpeta del repositorio cuenta con los siguientes elementos:

- Foto del circuito
- Esquema del circuito
- Sketch (nombre popular con el que se conocen los programas para Arduino. Su extensión es ".ino")

### Organización en equipos y Kit's

Para realizar las actividades, se organiza a los asistentes en equipos de hasta 6 personas. Cada equipo cuenta con una computadora y un kit.

#### Componentes del Kit:

- Contenedor: Utilizamos cilindros de pvc, pero puede ser cualquier otro contenedor.
- Placa Arduino Uno
- Cable USB
- Protoboard
- Componentes varios:
 - LED's
 - Resistencias
 - LDR
 - Cables
 - ...

### Introducción

Comenzamos presentando el taller, quienes somos, etc. Presentamos algunos conceptos que van a ser útiles luego:

- ¿Qué es el Software?
- Software Libre
- ¿Qué es específicamente un programa de computadora? (receta de cocina, secuencia de instrucciones, etc.)
- Hardware / Hardware Libre
- ¿Quién decide sobre los dispositivos que utilizamos?¿Podemos los usuarios incidir en el diseño?¿Podemos modificarlos?

### Incio

Pedimos a cada grupo que abra los contenedores de los kits y examine su contenido. Explicamos qué es Arduino y 
como esta compuesto (cable usb, entradas / salidas), microcontrolador.

Les pedimos que abran la carpeta de Desafíos, y que comiencen con "Blink". Las indicaciones que damos son:

- Armar el circuito según la foto o el equema.
- Abrir el archivo blink.ino, que es donde se encuentra el programa.- Leer el programa y sus comentarios (explicamos el concepto de comentar los programas) e intuir que es lo que hace el programa.
- Cargar el programa en el Arduino (explicamos como cargarlo utilizando la IDE de Arduino. También explicamos qué es la IDE).
- Luego, se les pide que leyendo el programa y los comentarios, intenten modificar el programa (en el caso del Blink, el tiempo de prendido y apagado
del led.

### Desarrollo

Continuamos con los siguientes desafíos, trabajando con la misma dinámica: construcción del circuito a partir de las imágenes, lectura 
y carga del programa, modificaciones.

A medida que los grupos van avanzando, generalmente a distintos ritmos, vamos explicando nuevos conceptos particularmente o 
en general para toda la clase.

##### Button 

Se introducen los siguientes elementos y se explica su funcionamiento:

- Protoboard o experimentor
- Resistencia 
- Botón pulsador

**Conceptos:**

- 5v y GND
- Resistencia eléctrica
- Condicional (if / else)

**Problemas/inconvenientes cocnocidos:**

- Destacar la descripción de las resistencias y su código de color, para que puedan elegir la correcta.
- A veces tienen dificultad en conectar los componentes en la protoboard, generalmente el botón. Reforzamos la idea de que intenten de varias formas,
si necesitan pinza o alguna otra herramienta la pueden usar, y que si se rompe no importa.s
