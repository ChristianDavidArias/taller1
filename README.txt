Clases principales:
-Main
-Logica
-Figura
-Texto

En la clase Main se encontraran los metodos principales
el setup, draw, mouseKressed y keyPressed principalmente.
En la clase Logica los metodos pintar, para que aparezcan los
elementos en el lienzo; press, para la interacciones con las 
teclas; click, para la interaccion del mouse con los elementos;
y fondo, para generar el cambio de color desde la clase logica.
Hay una clase Texto donde estara el contenido del texto con el 
que se haran las interacciones de la aplicacion y dentro de los
metodos estan los de leerTexto, dividirtexto, quitaletras, invertir,
y reemplazaletras que son las interacciones que se generaran en el 
texto.
Hay una clase abstracta que será Figura que tendra los atributos
principales de los elementos como los planetas y las estrellas,
posicion, tamañano, velocidad y color; y en los metodos estan 
pintar y mover.
Las clases hijas de Figura son Planeta,Estrellas y Soluna y como
metodos tendran pintar y mover.

