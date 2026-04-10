# Pensamiento-computacional

### CRONOGRAMA DE CURSO PENSAMIENTO COMPUTACIONAL 

En el curso PENSAMIENTO COMPUTACIONAL nos introduciremos en el uso del razonamiento lógico,
estructurado y creativo propio de la computación como herramienta para analizar y crear sistemas, flujos y comportamientos.
Comprender la lógica más que la sintaxis 

#### Unidad 1 -> introducción a la computación para el diseño 

Breve historia de la computación.
- Herramientas de documentación técnica: Introducción a Github y markdown.
- Relación entre dibujo y programación.
- Variables y condicionales.
- Organizar el código mediante funciones.

#### Unidad 2 -> Estructuras lógicas y comportamiento

- Bucles y repeticiones.
- Eventos y callbacks.
- Objetos y arreglos.
- Sensores y periféricos: mouse, teclado, webcam, otros.

#### Unidad 3 -> Proyecto computacional básico

- Introducción a interfaces simples y
prototipado en pantalla.
- Aplicación de los contenidos en un sistema funcional.
- Evaluación de la experiencia, lógica y
expresión del sistema.

## Evaluaciones 

Solemne 1   50%
Solemne 2   50% 

TOTAL 70% presentación examen ->  Examen 30% 

---
---
# 🌸 Clase 20/03 parte 1 - Historia breve de la computación 🌸
 

### **Primera fase abstracción**

- Máquina diferencial
Charles Babbage diseñó esta máquina en 1822 para automatizar el cálculo y la tabulación de funciones polinómicas. Estas son expresiones algebraicas formadas por la suma o resta de términos donde una variable x está elevada a potencias no negativas. Se trataba de un dispositivo mecánico de gran escala basado en engranajes; un acercamiento a la automatización de acciones rutinarias que antes realizaban las personas. Babbage nunca pudo construirla, pero años después, el Museo de Ciencias de Londres construyó en 1991 la Difference Engine No. 2 siguiendo los planos originales, y su diseño resultó ser totalmente correcto.

- Máquina Analítica

Diseñada por Charles Babbage entre 1834 y 1837, fue concebida para realizar cualquier tipo de cálculo establecido. Se considera la primera máquina de cálculo completamente automática (podía realizar operaciones más allá de la suma). Babbage dividió esta máquina en dos partes que conceptualmente se mantienen en la actualidad:
  
**El molino:** ->  **La CPU o Procesador**, donde se procesan los datos. 
El almacen -> **La memoria** donde se guardan los datos. 
Las targetas perforadas -> **El Software**  

### Ada lovelace 

Considerada una de las primeras programadoras de la historia y esta le abrió los ojos a Baddage sobre como construir la Máquina (analitica), ella al visitar el **Telar de jacquard** se inspiró para ayudar en el diseño del sistema
Además, fue la primera en crear un algoritmo para ser implementado a al máquina, este sirvia para calcular **Números de Bernoulli**, esto se considera **el primero programa de computación**

## Telar de jacquard (1801) 

Es el primer sistema de almacenamiento de información binaria (0 y 1, o sí o no).
El telar usaba un sistema de tarjetas perforadas para lograr diseños o dibujos complejos, si había agujero, la varilla pasaba (podemos entenderlo como 1 o "encendido") y, si no había agujero, la varilla chocaba contra la tarjeta y quedaba abajo (podemos entenderlo como 0 o "apagado").

-El telar de Jacquard introdujo tres conceptos fundamentales de la computación moderna:

1. La separación entre **Hardware*** y **Software** donde Hardware era la maquina fisica y Software serian las tarjetas perforadas, antes se tenia que reconstruir la máquina para cambiar la tarea, mientras con este sistema solo cambias de programa.
   
2. El sistema binario : Creó un sistema de lógica binaria.
 
3. El pixel y la imagen rasterizada: El tejido podemos entenderlo como una forma primigenia de la imagen de Mapa de bits. 

## La Máquina De Turing

Originalmente fue definida por el matemático inglés **Alan Turing** como una «máquina automática» en 1936. No es una máquina física, es un experimento mental (una máquina teórica). Turing imaginó una cinta infinita, un cabezal que lee/escribe símbolos, y un conjunto de reglas (estados).

> Define la Computabilidad Universal: Turing demostró que una máquina simple, con las instrucciones correctas, puede simular a cualquier otra máquina.

--- 

# Despertar visual 

- Artistas y algoritmos
Los intentos de mezclar el arte con la computación empezaron aproximadamente en 1960 

#### Artistas pioneros

EEUU

- Vera Molnár
- Manfred Mohr
- Georg Nees
- Frieder Nake
- Lillian Schwartz
  
Europa

- Hiroshi Kawano
  
- Computer Technique Group  Japón; y Waldemar Cordeiro, son pioneros 

# Etapa 3 Democratizacion del creative coding 

El Software libre nace formalmente en 1983, cuando Richard Stallman anunció el inicio del Proyecto GNU.

Su objetivo era crear un sistema operativo libre. En 1985 se publica el Manifiesto GNU y se funda la Free Software Foundation (FSF). 

Buscan garantizar 4 libertades esenciales:

 1. Libertad 0 (Uso): La libertad de ejecutar el programa como se desee, con
cualquier propósito.
 2. Libertad 1 (Estudio): La libertad de estudiar cómo funciona el programa y
cambiarlo para que haga lo que el usuario quiera. El acceso al código
fuente es una condición necesaria.
 3. Libertad 2 (Distribución): La libertad de redistribuir copias para ayudar a
otros.
4. Libertad 3 (Mejora): La libertad de mejorar el programa y hacer públicas
las mejoras, para que toda la comunidad se beneficie. El acceso al código
fuente es necesario.

Principios fundamentales adicionales de la FSF:

1. Libertad, no precio: El software libre es una cuestión de libertad
de los usuarios de computadores, no de precio.

2. Copyleft: Se promueve la distribución bajo términos de copyleft,
que garantizan que el software y sus versiones modificadas sigan
siendo libres.

3. Lucha contra restricciones: Campañas activas contra patentes
de software, Gestión Digital de Restricciones (DRM) y otras
amenazas a la libertad de los usuarios.

4. Desarrollo del proyecto GNU: Fomento del desarrollo de un
sistema operativo completamente libre.

---

Hay diferencia entre open source y Software Libre

#### Open sourse 
"Colaboración". El código abierto permite que más ojos revisen errores y mejoren el producto.

#### Software Libre
"Libertad" El usuario debe tener el control de su informática.


---
---

# 🌸 Clase 20/03 parte 2 - Markdown 🌸

- GitHub es una plataforma basada en la nube donde puedes almacenar, compartir y trabajar junto con otros usuarios para escribir código

Titulos

# Titulo Grande h1
## Subtitulo h2
### Pequeño
###### Mas pequeño  h6

---
## Tipos de texto

**Negrita**

*Cursiva*

~~Tachado~~

---
## Listas 

Con puntitos

- Agua
- Pan
- Harina
   * azucar
   * canela

Numeradas 

  1. Primero
  2. Segundo
  3. Tercero
     1. Firts

---
## Linea separadora 

---

## Links 

[google](https://www.google.com/?hl=es)

## Imagenes

![gatos](link de la imagen)

## Bloques 

> habia una vez ........
> 
>> pero paso......

## Emojis

:rocket -> no me funciono pero tmb se puede pegar directamente 

---
---

# 🌸 Clase 27-03-2026  Introducción al pj5 🌸

  #### ¿Que es un algoritmo? 

Es una secuencia instrucciones paso a paso, lógicas, definidas, ordenadas y finitas que
permiten solucionar un problema o realizar una tarea específica.

Debe ser preciso, ordenado, tiene que terminar en algun momento, debes obtener siempre el mismo resultado.

INPUT:  Entrada  --->  PROCESO: Algoritmo ---> Output : Salida resultado final 

### ¿Que es un diagrama de flujo?

Representación gráfica de un algoritmo o de lospasos de un proceso. En programación, se utiliza como una herramienta de planificación para visualizar la lógica de un programa antes de escribir una sola línea de código.

### Lenguajes de programación 

Existen entre 700 y 900 lenguajes de programación que se utilizan en la industria ( me acuerda a la programacion que son solo moo jjajaj) 

Algunos más populares 

- Python, Java, C++ , C# , JavaScript, TypesScript etc...


### P5.JS

Utiliza principalmente el lenguaje de JavaScript, es un vocabulario especializdo para dibujar,animar y crear cosas visuales de forma más sencilla

Hay funciones maestras
- Setup: Se ejecuta una sola vez para crear el lienzo, configura el entorno inicial.  

- Draw: se ejecuta en un bucle infinito lo que te permite crear animaciones, crea movimiento y responde a la interacion en tiempo real
  
---

createCanvas : el tamaño del lienzo (W,H)

background: designa el color del lienzo en RGB los primeros 3 rojo verde azul, y cuarto le puedes dar transparencia - [htmlcolorcode](https://htmlcolorcodes.com/) 

Figuras geometricas 

<img width="585" height="178" alt="image" src="https://github.com/user-attachments/assets/c9f778f4-99cc-4608-85b4-04806c5855e2" />

Tamaño del borde 

strokeweight(); : ancho

noStroke(); para que no tenga borde 

Fill(); 

establece el color del relleno de las figuras (RGB)

Arc(); primero se activa el angleMode(DEGREES) en la parte de funcione 
arc(x,y,w,h,start,stop);

<img width="209" height="142" alt="image" src="https://github.com/user-attachments/assets/ae617cd1-e156-4886-a79f-83a7cd9809e0" />

----

[Desafio 1](https://editor.p5js.org/amanda.venegas1/sketches/3sZlCZAKz)

[Desafio2]( https://editor.p5js.org/amanda.venegas1/sketches/9wSdfU8Yw)

---
# ENTREGA 09/04/2026 

Deben inspirarse en alguna pintura de algún artist@ geométric@ o geométric@ abstract@ y hacer un dibujo
en papel milimetrado, usando solamente figuras primitivas 2D; puntos, lineas rectas, cuadrados,
rectángulos, círculos, elipses, triángulos y arcos (medialuna). Usar todas las figuras mencionas.

Mi primera idea de composicion era esta : 

![entrega](https://github.com/user-attachments/assets/e827c599-51dd-4659-a2a0-6ec9a76eb53c)

Despues cambio a esto : 

<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/af5401bd-871a-4452-a78f-a174d7159a35" />

Artista referente: 

Mi inspiración principal fue Wassily Kandinsky pintor ruso y pionero del arte abstracto. Mi proceso no se basó en una obra específica, sino en una actividad inspirada en él vista en una imagen : lanzar dados y dibujar lo señalado. 

También tuve como referencia visual la obra "Klinom krasnym bey belykh" (Golpea a los blancos con la cuña roja)

<img width="227" height="277" alt="image" src="https://github.com/user-attachments/assets/46a08bba-4c48-4bae-8097-1fae00a850f6" />

Desarollo en el P5JS: 

Lo primero que realicé fue cambiar el tamaño del lienzo a 500 × 500 px. Luego, ajusté el fondo a color blanco con valores RGB (250, 250, 250) que despues cambie por un color mas neutro cafe

Para llevar mi diseño desde el formato tradicional a la pantalla, hice un cálculo para determinar la equivalencia de coordenadas. Mi lienzo original estaba dividido en una cuadrícula de 25 × 25, por lo que multipliqué cada coordenada por 20 para escalarla correctamente.

Este es un cálculo proporcional.
Por ejemplo, si un punto estaba en (2, 5), lo multiplicaba por 20:
(2 × 20, 5 × 20) → (40, 100) en pantalla.

De esta manera, fui ubicando las primeras figuras: triángulos, rectángulos, cuadrados, medios círculos, círculos, líneas y puntos. También utilicé el comando noStroke, que más adelante me generó algunas dificultades con los puntos y las líneas.

Las principales complicaciones que encontré fueron:

- El medio círculo y el círculo, ya que una de las medidas corresponde al diámetro total y no al radio.
- El medio círculo en particular, porque al inicio no se dibujaba correctamente, esto se debía a que había olvidado incluir angleMode(DEGREES); en la función setup.
- El posicionamiento de las figuras, es decir, cuál debía ir encima y cuál debajo.
- Los puntos y las líneas, ya que al tener activado noStroke, no se actualizaban y solo se dibujaban una vez.
- El cuadrado no se genera colocando todos los puntos si no que solo la cordenada de arriba mas el tamaño.
- el arco que debeia ser del mismo color del fondo.
- Uno de mis mayores miedos en este trabajo era que quedara muy simple mi dibujo por eso a medida le empece agregar mÁs elementos.
- Y luchar con la pantalla de mi laptop ya que no tiene una buena calibracion de color lo cual al verlo en otras pantallas me di cuenta que se veia mal :c 

Algunas de las cosas tuve que investigar en la misma pagina [reference](https://p5js.org/es/reference/)


### Mi proceso 

![progreso](https://github.com/user-attachments/assets/b57511c2-50b4-4123-9e9b-7410e8700681)

## Resultado 

<img width="375" height="374" alt="image" src="https://github.com/user-attachments/assets/8c0b3db2-ad0f-4052-a508-a11dcdeff2a8" />

  










