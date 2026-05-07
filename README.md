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






