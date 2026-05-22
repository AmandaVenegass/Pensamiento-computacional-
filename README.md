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

Mi inspiración principal fue Wassily Kandinsky pintor ruso y pionero del arte abstracto. Mi proceso no se basó en una obra específica, sino en una actividad inspirada en él, vista en una imagen : lanzar dados y dibujar lo señalado. 

También tuve como referencia visual la obra "Klinom krasnym bey belykh" (Golpea a los blancos con la cuña roja)

<img width="227" height="277" alt="image" src="https://github.com/user-attachments/assets/46a08bba-4c48-4bae-8097-1fae00a850f6" />

Desarollo en el P5JS: 

Lo primero que realicé fue cambiar el tamaño del lienzo a 500 × 500 px. Luego, ajusté el fondo a color blanco con valores RGB (250, 250, 250) que despues cambie por un color mas neutro cafe

Para llevar mi diseño desde el formato tradicional a la pantalla, hice un cálculo para determinar la equivalencia de coordenadas. Mi lienzo original estaba dividido en una cuadrícula de 25 × 25, por lo que multipliqué cada coordenada por 20 para escalarla correctamente.

Este es un cálculo proporcional.
Por ejemplo, si un punto estaba en (2, 5), lo multiplicaba por 20:
(2 × 20, 5 × 20) → (40, 100) en pantalla.

De esta manera, fui ubicando las primeras figuras: triángulos, rectángulos, cuadrados, medios círculos, círculos, líneas y puntos. También utilicé el comando noStroke, que más adelante me generó algunas dificultades con los puntos y las líneas.

### Mi proceso 

![progreso](https://github.com/user-attachments/assets/b57511c2-50b4-4123-9e9b-7410e8700681)

Las principales complicaciones que encontré fueron:

- El medio círculo y el círculo, ya que una de las medidas corresponde al diámetro total y no al radio.
- El medio círculo en particular, porque al inicio no se dibujaba correctamente, esto se debía a que había olvidado incluir angleMode(DEGREES); en la función setup.
- El posicionamiento de las figuras, es decir, cuál debía ir encima y cuál debajo.
- Los puntos y las líneas, ya que al tener activado noStroke, no se actualizaban y solo se dibujaban una vez.
- El cuadrado no se genera colocando todos los puntos si no que solo la cordenada de arriba, más el tamaño.
-  luchar con la pantalla de mi laptop ya que no tiene una buena calibracion de color lo cual al verlo en otras pantallas me di cuenta que se veia raro
- y mi torpeza por que borre mi codigo en clase perooo tenia un respaldo antiguo, pero pude avanzar a partir de eso

Algunas de las cosas tuve que investigar en la misma pagina [reference](https://p5js.org/es/reference/)

## Resultado 

<img width="374" height="375" alt="image" src="https://github.com/user-attachments/assets/caddf2f8-7f37-4e35-95e7-557402dae0a4" />

---
# 🌸 Clase 10/04 - Datos dinámicos "Variables" 🌸

### ¿Que es una variable? 

- Una variable es un nombre que se usa para guardar un valor que puede cambiar.
Es como una caja donde puedes guardar datos (números, texto, etc.) y usarlos después.

### Variable MouseX y MouseY 

- mouseX: sigue la posición horizontal del ratón.
- mouseY: sigue la posición vertical del ratón.

Si pongo background() en draw(), el fondo se borra todo el tiempo. Si lo pongo en setup(), solo se borra una vez.

La función draw() por defecto se ejecuta aproximadamente a 60 fotogramas por segundo.

mousePressed(): es una función que se ejecuta cuando se presiona el botón del mouse. 

<img width="762" height="345" alt="image" src="https://github.com/user-attachments/assets/b8ebb5d4-b0fa-47c4-88d1-a907bf8ad92f" />
<img width="762" height="390" alt="image" src="https://github.com/user-attachments/assets/2887e02b-d757-4860-979d-923da8f75130" />

### ¿Como hago mi propia variable? 

Para declarar una variable podemos usar

- **let** para variables dinámicas 
- **const** para variables constantes

  1. DECLARAR TU VARIABLE
  2. INICIALIZA TU VARIABLE
  3. USA TU VARIABLE

### Incrementation operators aumentar el valor de una variable en 1 o más.
Ejemplo:

let x = 100;   
draw   
x= x +5  O  x += 5  

esto sirve para todas las operaciones matematicas 

### Javascript Objects

- Sirven para guardar y organizar información en una sola estructura.  
- Se forman con pares de clave y valor, como nombre y edad dentro de una persona.  
- Permiten acceder y manejar información de forma más ordenada y fácil de usar.  

let persona = {   
  nombre: "Ana",    
  edad: 15,    
  ciudad: "Santiago"    
};    

### Random()fuction

Su trabajo es devolver un número aleatorio dentro de un rango que tú definas.

- random(): Si no pones nada, devuelve un número decimal entre 0 y 1
- random(máximo): Devuelve un número decimal entre 0 y el máximo que elijas.
- random(mínimo, máximo): Devuelve un número decimal entre esos dos valores.

### (width , height); 
Variables integradas en p5, que correspondena los valores definidos en el createCanvas.

### (windowWidth, windowHeight);
Variables integradas en p5, que permiten ajustar el tamaño del lienzo al tamaño de la ventana delnavegador. Se usan en el createCanvas.

### map fuction 
Esta función nos permite convertir un valor de un rango a otro.

"map(valor, min_original, max_original, min_nuevo, max_nuevo)" 
---
Desafio 

1. Hacer un duplicado del dibujo que entregaron para la solemne.
2.Darle movimiento al dibujo en p5.js.
3.Usando cada una de las variables y funciones que aprendimos hoy;

•mouseX mouseY
•let creado por mi
•Javascript object
•Random fuction
•Width height
•WindowWidth WindowHeight
•Map función

Mi entrega : https://editor.p5js.org/amanda.venegas1/sketches/Wy4-n-Mfx 
---

# 🌸 Clase 16/04 - Transformaciones y condicionales 🌸

### Rotacion de figuras 

La funcion *rotate()* sirve para rotar el sistema de cordenadas 

"rotare(angulo)": ->  este angulo se puede trabajar de dos maneras en radianes o en algulos  

O° son 0 radiales   
90° seria PI/2  
180 son Pi radiales     
360 son TWO_PI     

TWO_PI 360 ̊  
PI 180 ̊  
HALF_PI 90 ̊  
QUARTER_PI 45 ̊  

- Entonces **rotate()** sirve para rotar elementos.  
- Siempre rota alrededor del punto de origen (0,0).
- Se recomienda usar con **translate()** y en algunos casos con **rectMode(CENTER);**  

### translate()

Sirve para transladar el punto de origen (0,0) a otra cordenada de mi canvas 

### push() and pop ()

Funciones que trabajan juntas como sistema de memoria temporal para el estilo y transformaciones del lienzo sirve para que los cambios que hagas como mover o rotar no afecten a todo lo que dibujes después.

### scale () 
Función scale() ajusta la escala del sistema de coordenadas actual por el factor especificado.


---

# Condicionales 

Logica condicional 

### Expresion booleana:  
Una expresión booleana es cualquier enunciado, dato o instrucción que, al ser evaluado, solo puede arrojar uno de dos valores posibles:

Verdadero (True) o Falso (False).  

**Es como hacer una afirmación y preguntarse: ¿esto es cierto o no?**

5 > 3 → verdadero  
10 == 7 → falso  

Para construir este tipo de expresiones se utilizan **3 tipos de elementos:**

1.  Operandos (o Valores): 

Son los datos básicos que se evalúan. Pueden ser:

- Variables: (como x, y o mouseX, mouseY, etc).

- Constantes o Literales: Valores fijos como 5, "Hola" o los mismos valores booleanos True y False.

2. Operadores de Comparación:

Permiten contrastar dos valores.

== (Igual a)  
!= (Diferente de)  
> o < (Mayor o menor que)
> >= o <= (Mayor o igual / Menor o igual)  

3. Operadores Lógicos: 

Sirven para combinar varias expresiones.

AND (&&): Es verdadero solo si ambas partes son verdaderas.  
OR (||): Es verdadero si al menos una de las partes es verdadera.  
NOT (!): Invierte el valor (si era verdadero, pasa a ser falso).  

(5 > 3) AND (2 < 4) → verdadero  
(10 == 5) OR (3 > 1) → verdadero  
NOT (7 < 2) → verdadero 

<img width="879" height="495" alt="image" src="https://github.com/user-attachments/assets/7ea65db7-1bf1-4c79-908f-0a31237ee85b" />
<img width="879" height="495" alt="image" src="https://github.com/user-attachments/assets/aaa14145-a2bf-46a3-80d1-6a33172ec84c" />
<img width="878" height="493" alt="image" src="https://github.com/user-attachments/assets/6d4db318-8a4d-4f61-b099-f721b365a2e6" />


---
---
# Sentencia condicional

### ¿como puede un programa tomar diferentes caminos ?
Comparando valores 

Permite a un programa tomar decisiones "si se cumple esta condición, haz esto; si no, haz otra cosa”.

## If - else if - else 

La sentencia if es una estructura especial que existe en casi todos los lenguajes de programación; toma una condición –expresada como un booleano– y ejecuta una pieza de código contenida dentro de las llaves { }

If -> if (condicion) {accion}

Ejemplo :
Si la edad es mayor o igual a 18, se muestra el mensaje 'Eres mayor de edad'. De lo contrario, se muestra 'Eres menor de edad'."

edad = 18

if (edad >= 18) {
    imprimir("Eres mayor de edad")
} else {
    imprimir("Eres menor de edad")
}

## Variantes  else if 

if (Si...): Es la primera pregunta. Si es verdad, entra aquí y ignora todo lo demás.

else if (Pero si...): Solo se pregunta esto si la primera fue falsa. Puedes tener tantos como quieras.

else (Si nada de lo anterior funcionó...): Es tu plan de reserva, lo que pasa si ninguna condición se cumplió.

Ejemplo 

Si la nota es mayor que 6 sale mensaje de aprobado si no cumple con lo anterior peros si la nota es mayor que 4 sale mensaje de recuperacion y si no cumple ninguna de las anteriores sale mensaje de reprobado 

if (nota >= 6) {  
    imprimir("Aprobado")  
} else if (nota >= 4) {  
    imprimir("Recuperación")  
} else {  
    imprimir("Reprobado")  
}  

--- 
Tarea / Desafio 

Deben crear un Sketch LIBRE, que incluya:

- Varias figuras geométricas
- Rotación
- Translate
- Push Pop
- Scale
- Texto https://p5js.org/es/search/?term=text
- Imagen https://p5js.org/es/search/?term=image https://editor.p5js.org/PoliMujica/sketches/nm0fj2seC
- 2 sentencias condicionales completas (If - else if - else)

Mi entrega : https://editor.p5js.org/amanda.venegas1/sketches/baVQi8Xlj

---
---
# Cuatro pilares 

1. Descomposición
2. Reconocimiento de patrones
3. Abstracción
4. Algoritmos 

## 1- Descomposición 
"Dividir para conquistar"

Consiste en tomar un problema grande y complejo y romperlo en partes más pequeñas y
manejables.

- En diseño: Si quieres visualizar la "Brecha Salarial", no programas todo de una vez.
Primero diseñas cómo se ve el "Sueldo A", luego el "Sueldo B", luego la "Interacción" y
finalmente el "Fondo".

- En el código: Se traduce en el uso de Funciones Propias. En lugar de un draw() gigante,
tienes una función dibujarIconos() y otra calcularDiferencia(), etc.

## 2- Reconocimiento de patrones 

"Encontrar similitudes"

Es observar tendencias o regularidades dentro de un problema. Si algo se repite o sigue una
lógica constante, podemos automatizarlo.

- En diseño: Notas que para representar a 100 personas, no necesitas dibujar 100 veces.
Notas que todas son un círculo con una posición x distinta.

- En el código: Se traduce en el uso de Bucles (for). Si hay un patrón, el código lo repite por
ti con solo tres líneas.

## 3.Anstracción 

"Lo importante vs. el detalle"

Es filtrar la información innecesaria y quedarse solo con las características que definen el
problema. Es crear una representación simbólica de la realidad.

-  En diseño: Para representar la "presión social" no necesitas dibujar a toda la sociedad;
quizás un círculo que se achica cuando el mouse se acerca es suficiente.

-  En el código: Se traduce en el uso de Variables y la función map(). Una posición de
mouse (mouseX) se "abstrae" para convertirse en un valor de opacidad o miedo.


## 4- Algoritmos 

"La receta paso a paso”

Es el diseño de una serie de reglas ordenadas para resolver el problema. Es el "plan de
acción" que debe seguir el sistema.

- En diseño: Es el flujo de la experiencia. "Si el usuario hace esto, pasa aquello; si no,
pasa esto otro”.
- En el código: Se traduce en el Diagrama de Flujo y en las Condicionales (if/else). Es el
mapa lógico que conecta todas las partes anteriores.

---
# Tipos de interacción 

### 1. Interacción Discreta (Eventos)

Es cuando curre un evento específico (clic) y el sistema responde con una acción única (aparecen
círculos). Es un interruptor de "encendido/apagado" o "acción/reacción".

- En el código: Se suele usar dentro de la función mousePressed() o con un if(mouseIsPressed).

### 2. Interacción Continua (Input de Datos)
   
Es cuando el sistema reacciona constantemente al movimiento o estado del usuario, sin necesidad
de hacer algo especifico (clic).

- En el código: Usar mouseX o mouseY directamente para afectar el tamaño, color o velocidad
de algo.

## Funciones propias 
se divide en ** Modularidad** y **Reusabilidad**



---
---

## Solemne 2 

1. El Desafío
   
El objetivo de esta Solemne no es demostrar expertiz técnica en programación, sino demostrar capacidad de razonamiento
lógico y sistémico. Deberán diseñar un "organismo visual" en p5.js que funcione mediante reglas preestablecidas para
visibilizar una problemática de genero.
Lo más importante es cómo traduces un problema social a una regla de comportamiento computacional.

2. Marco Conceptual: Las 4 Columnas del PC
   
Su proyecto será evaluado bajo los cuatro pilares del pensamiento computacional:

- Descomposición: ¿Dividiste tu problemática en partes más pequeñas y manejables (funciones)?

- Reconocimiento de Patrones: ¿Usaste ciclos para crear estructuras o repeticiones con sentido (loops -for)?

- Abstracción: ¿Lograste que un movimiento o cambio visual represente un concepto real (ej. usar map para que el mouse
represente "presión social")?

- Algoritmos: ¿Tu diagrama de flujo explica paso a paso cómo funciona tu sistema?

---

# 🌸 # sesión 06 - Clase 15/05 LOOPs while and for 🌸

### ¿Qué es un loop?
- Es algo que se repite en bucle

#### ¿Los loops son infinitos? 
Si 

### Definición de LOOP

Informática. Serie de instrucciones que se repiten indefinidamente mientras no se cumpla una condición previamente establecida. 

## LOOP 
Es una estructura de control que permite ejecutar un bloque de instrucciones de manera repetida mientras se cumpla una condición específica o hasta que se alcance un estado determinado.

# While 
Los bucles while son útiles para repetir instrucciones mientras una condición sea verdadera. Son como sentencias if que se repite.

while(condición booleana){ejecuta este codigo si este true}

<img width="509" height="114" alt="image" src="https://github.com/user-attachments/assets/bc43b357-0487-4fd0-be1f-c2a994f43fbc" />

- EJEMPLOS DE LA PROFE
- 
- Primero : https://editor.p5js.org/amanda.venegas1/sketches/YZHZTzuYO
- Segundo : https://editor.p5js.org/amanda.venegas1/sketches/XZfGBk240
- Tercero : https://editor.p5js.org/amanda.venegas1/sketches/Up7uBC3WL

Se define primero la x 

Loop repite el objeto no anima 

# For
Este se usa mas que el while 

Una forma de repetir un bloque de código cuando se conoce el número de iteraciones. Los bucles "for" son útiles para repetir instrucciones un
número determinado de veces. Son una especie de SHORTCUT para hacer loops y siempre tienen 4 elementos:

1. Inicialización de una variable
2. Condición booleana (V-F)
3. Actualización ( Incrementación o decrementación)
4. Lo que queremos que pasé cuando la condición sea TRUE

for (inicialización variable; condición booleana; actualización){ Lo que queremos que pase cuando la condición sea verdadera }                          
// Integra la variable dentro del comando 

<img width="310" height="111" alt="image" src="https://github.com/user-attachments/assets/f5db669e-8376-4ed4-b523-b563c39f838f" />

Ejemplo de la profe 

- Cuarto : https://editor.p5js.org/amanda.venegas1/sketches/RAxBfThLb
- Quinto : https://editor.p5js.org/amanda.venegas1/sketches/Eo_5XA9NM

---

# NESTED LOOPS 

Un loop dentro de otro loop
Un for dentro de otro for

for (inicialización variable; condición booleana; actualización){

Lo que queremos que pase cuando la condición sea verdadera

for (inicialización variable; condición booleana; actualización){
}
Lo que queremos que pase cuando la condición sea verdadera
}

<img width="371" height="239" alt="image" src="https://github.com/user-attachments/assets/615f0d93-64ae-40e5-8c51-7bef02941d70" />

Ejemplo de clase 

- https://editor.p5js.org/PoliMujica/sketches/BfZygN32B
- https://editor.p5js.org/amanda.venegas1/sketches/ap9yc5m5g

# FrameCount

Variable numérica que registra la cantidad de fotogramas dibujados desde que comenzó el boceto. El valor de "frameCount" es 0 dentro
de "setup()". Se incrementa en 1 cada vez que finaliza la ejecución del código en "draw()".

Ejemplo 

https://editor.p5js.org/amanda.venegas1/sketches/uAHxFltC6

---

# 🌸 Clase 22/05 Solemne 2 🌸 

## Manspreading -  Amanda Venegas 

Mi proyecto busca representar de manera sencilla el fenómeno del manspreading, buscando evidenciar cómo este comportamiento afecta el espacio de otras personas en lugares públicos.

### ¿Qué es el manspreading?

El manspreading es una costumbre en la que algunos hombres abren excesivamente las piernas al sentarse, ocupando más espacio del necesario y llegando a incomodar a la persona que está al lado.
Aunque puede parecer una acción cotidiana o automática, ha sido analizada como una práctica que evidencia el uso desigual del espacio compartido.

Para desarrollar esta idea, utilicé como escenario el metro, ya que es un lugar donde esta práctica puede ocurrir con frecuencia debido a la cercanía entre las personas y la falta de espacio personal. El metro evidencia cómo pequeñas acciones pueden tener un impacto directo en los demás.

En la escena se observa el dibujo de un hombre y una mujer sentados uno al lado del otro. A través de la interacción, el personaje masculino comienza a expandirse progresivamente, ocupando cada vez más espacio.

La idea principal del proyecto es mostrar de forma visual e interactiva cómo, con cada clic, el personaje va ocupando más espacio con sus piernas. A mayor cantidad de clics, mayor es el espacio que invade dentro del asiento.

Este proyecto se relaciona con la problemática de género porque representa cómo ciertos comportamientos cotidianos, como el manspreading, pueden reflejar dinámicas de desigualdad en el uso del espacio público. Aunque no siempre es intencional, evidencia cómo el espacio puede ser ocupado de manera desproporcionada, generando incomodidad en otras personas.

El input corresponde a las acciones del usuario al hacer clic sobre la pantalla. Esto modifica variables del programa, como el tamaño del personaje y la apertura de sus piernas, que van aumentando progresivamente. Como resultado, el personaje ocupa cada vez más espacio dentro de la escena, lo que provoca que la mujer se aparte, mostrando incomodidad y enojo.

Lo que busco es mostrar situaciones cotidianas desde otra perspectiva, evidenciando cómo acciones pequeñas pueden tener un impacto en la experiencia de otras personas en espacios compartidos.

<img width="530" height="528" alt="image" src="https://github.com/user-attachments/assets/c952ae96-5887-430b-bc97-d176c587ad48" />

<img width="532" height="528" alt="image" src="https://github.com/user-attachments/assets/e04e34f1-184b-4c19-9324-59b54c3c2465" />

---

<img width="475" height="1183" alt="Sin título (1)" src="https://github.com/user-attachments/assets/a7bf3bb6-e238-4d05-b0e2-f0465eaa131d" />

---

### Referentes

Me inspiré en una imagen encontrada en RedNote, aunque no logré identificar al autor original.

<img width="451" height="640" alt="image" src="https://github.com/user-attachments/assets/26182615-0403-4dac-8791-052bee865f94" />

Universitat Oberta de Catalunya. (2023, 22 de marzo). Mansplaining, manspreading y gaslighting. UOC News. https://www.uoc.edu/es/news/2023/074-mansplaining

---
### Link de trabajo : https://editor.p5js.org/amanda.venegas1/sketches/Ia93yVeeX
---

### Codigo 

```javascript
// Estas son variables para guardar las imagenes 
let imagenFondo;
let chicaI;
let chicoI;
let enojoI;

// Declare y agrupe variables 

let chico = {  // Todas las variables del chico 
  
// Posicion de la imagen del chico en x y Y 
  x: 546,
  y: 380,
  
// Tamaño de la imagen
  
  ancho: 290,
  alto: 360,
  
// Medida del lado del cuadrado azul 
  lado: 120,

  // Variables de la posición de las piernas derecha,izquierda y Tamaño 
  piernaD: 570,
  piernaI: 480,
  tamPierna: 60
};


let chica = { // Variables de la chica 
  x: 180, // Posición de la imagen de la chica en x 
  y: 200, // Posición de la imagen de la chica em y 
  circuloX: 310, // Valor de x del circulo que es la cabeza 
};

let click = 0; // Cuenta cuantas veces el usuario hace clic 
let rojo; // Variable de color rojo despues usada en el map 

function preload() { // Sirve para cargar imagenes antes que empiece el programa 
  imagenFondo = loadImage("metrofondo.jpg");
  chicaI = loadImage("chica.png");
  chicoI = loadImage("chico.png");
  enojoI = loadImage("enojo.png");
}

function setup() { // Es una funcion que se ejecuta solo una vez en el prograama 
  createCanvas(800, 800); // Crea un lienzo en x,y 
  frameRate(20); // Es una funcion que limita cuantas veces se ejecuta el draw se mide en fps 
}

function draw() {  // Es una función que se ejecuta constantemente en bucle mientras este funcionando 
// Esto sirve para que el programa ejecute estas funciones en ese orden
// Separe cada elementos en funciones para mantener el codigo mas ordenado y mas facil de entender
  backgroundS(); // Organiza los elementos del fondo 
  patron(); // El patron de puntos 
  boy(); // Dibuja los elementos del chico 
  girl(); // Dibuja los elementos / partes de la chica 
  titulo(); // Dibuja los elementos del titulo
  enojo(); // Dibuja la imagen de simbolo de enojo 
}

// Funcion de los elementos del fondo - map - imagen del fondo - lineas 

function backgroundS() {

  rojo = map(chico.ancho, 290, 350, 0, 255); // Para convertir un valor de un rango a otro rango de 0 a 255  map(valor, mínimo1, máximo1, mínimo2, máximo2)

  background(rojo, 0, 0); // Crea un fondo en rgb ( rojo, verde y green )

  image(imagenFondo, 0, 0, width, height);  // Carga la imagen de fondo en la posicion 0,0 oero con medidas del ancho y alto del lienzo 

  fill(rojo, 0, 0, 150); // Rellena el lienzo de un cuadrado rojo con cierta trasparencia 
  rect(0, 0, width, height); // Tamaño del cuadrado rojo que tambien mide a}el mismo ancho y alto del lienzo  
}

function patron() { // Cree una funcion solo para el patron del fondo 

  strokeWeight(3); // Grosor del punto 
  stroke(0); // Color negro 
 
  for (let x = 300; x < 750; x += 20) { // Comienza a dibujar en  300 del eje X y avanza hasta 750, saltando de 20 en 20.
    for (let y = 0; y < 300; y += 20) { // Comienza a dibujar en  0 del eje Y y avanza hasta 300, saltando de 20 en 20.
      point(x, y); // Dibuja un punto en esa coordenada.
    }
  }
}

function girl() { // Elementos de la chica 

  noStroke(); // Quita el borde de las figuras.

  image(chicaI, chica.x, chica.y); // Coloca la imagen en los valores de x,y 

  
  // Si el usuario ha hecho exactamente 6 clics el circulo cambia random el color en rojo, verde y azul y si no hay 6 clics deja el color fijo en esos valores 
  if (click == 6) { 

    fill(random(255), random(255), random(255)); 
    circle(chica.circuloX, 285, random(200));

  } else {

    fill(238, 157, 225);
    circle(chica.circuloX, 285, 120); // circle(posiciónX, posiciónY, diámetro);
  }
}



function boy() {  // Esta función se encarga de dibujar al personaje chico.

  push(); // Guarda la configuración actual del dibujo (colores, modos)

  fill(91, 69, 169); // Define el color de relleno
  noStroke(); // Quita el borde de las figuras.
  
// pierna izquierda 
  rect(chico.piernaI, 540, chico.tamPierna, 220);
  
// pierna derecha 
  
  rect(chico.piernaD, 540, chico.tamPierna, 220);

  imageMode(CENTER); // Hace que las imágenes se dibujen desde el centro.
  rectMode(CENTER); // Hace que los rectángulos también se dibujen desde el centro.

  image(chicoI, chico.x, chico.y, chico.ancho, chico.alto); // Dibuja la imagen del chico. (iamgen,x,y, ancho , alto)

  square(chico.x, chico.y - chico.alto / 2 + 105, chico.lado); // Dibuja un cuadrado encima del personaje ajustando su posición para que quede sobre la cabeza. chico.y - chico.alto / 2 + 105  ajusta la altura para colocarlo sobre la cabeza
  
  pop(); // Vuelve a la configuración original para que los cambios de esta función no afecten al resto del programa 
}


function titulo() {  // Esta función se encarga de dibujar el título 

  fill(255); // Define el color blanco para el texto.
  textSize(30); // Define el tamaño del texto en pixles 
  textFont("Georgia"); // Declara que tipografia utilizar 

  text("¿Como ocupas el espacio?", 250, 60); // Dibuja el titulo (texto, posición X, posición Y)

  fill(0); // Rellena el color en valores rgb pero solo esta declarado en 0 que es negro

  quad(0, 0, 800, 0, 800, 20, 0, 20); // Dibuja un cuadrilátero en la parte superior de la pantalla en sentido horario 
  
  quad(0, 800, 800, 800, 800, 780, 0, 780); // // Dibuja un cuadrilátero en la parte superior de la pantalla en sentido horario 
}

function enojo() { // Elementos de la imagen enojo 
  
   if (click >= 5) { // Despues de 5 clics realiza lo siguiente 
     
     push (); //  Guarda la configuración actual del dibujo 
    translate(300, 250); // Mueve el sistema de coordenadas a la posición (300, 250)
    rotate(frameCount * 0.05); // Rota la imagen continuamente con el tiempo, frameCount es un contador de cuadros

    imageMode(CENTER); // Hace que la imagen se dibuje desde su centro.
    image(enojoI, 0, 0, 70,70); // Coloca la imagen en el lienzo en image(imagen, x, y, ancho, alto);
     
     pop(); // Cierra la configuracion  para que no afecte a las siguientes partes del programa 
     
     
}
}

function mousePressed() { // // Esta función se ejecuta cada vez que el usuario hace clic con el mouse.

  if (click < 6) { // Si el usuario da menos de 6 clics ejecuta lo siguiente 

    chico.ancho += 10; // Aumenta el ancho de la imagen del chico 
    chico.alto += 25; // Aumenta el alto 
    chico.lado += 15; // Aumenta el tamaño del cuadrado del chico 

    chico.piernaD += 15; // Mueve la pierna derecha hacia la derecha 
    chico.piernaI -= 25; // Mueve la pierna izquierda hacia la izquierda 
    chico.tamPierna += 5; // Aumenta sutilmente el tamaño de las piernas.

    click++; // Suma 1 al contador de clics.
  }

  if (click == 5) { // Si el usuario dio 5 clicks realiza esto 

    chica.x -= 50; // Mueve a la chica a la izquierda 
    chica.circuloX -= 50; // Mueve también el circulo 
  }
}
```









