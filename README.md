# CPP-NumbersAndLettersGameV2
Another version of the numbers and letters game

# Introducción
En esta práctica hemos desarrollado una clase llamada Solver.
Esta clase nos resuelve el juego de las letras dado un diccionario y un set de letras.
Admite dos modos de juego diferente, por longitud en el que el programa obtiene las palabras
dado un vector de letras disponibles que son más largas, o por puntuacion, en que el programa
devuelve las palabras del diccionario que pueden formarse con dicho vector y que tienen la mayor
puntuación según el LetterSet. Nuestro ejecutable pondrá a prueba a la clase pasándole una serie
de parámetros para jugar en las dos modalidades que se nos ofrece.

# Ejecutables

## Partida letras

Dado como argumentos dos archivos, uno con un LetterSet y otro con un Dictionary respectivamente,
u caracter P o L que indica el modo de juego puntuación y longitud respectivamente y un entero que
indica el numero de letras con el que vamos a jugar. El programa muestra por pantalla las mejores
soluciones para esas letras y el diccionario.

> __partida_letras__ \<FicheroLetterSet\>  \<FicheroDictionary\> \<(char)GameMode(P/L)\> \<(int)CantidadLetras\>

@param <FicheroLetterSet> Fichero que contiene las letras con la cantidad de veces con las que se pueden jugar en una partida así
como la puntuación asociada a cada una de ellas
@param <FicheroDictionary> Fichero que contiene todas las palabras con las que se puede jugar
@param <(char)GameMode(P/L)> 'P' si jugamos a puntuación, 'L' si jugamos a palabra más larga (longitud)
@param <(int)CantidadLetras> entero que indica el número de letras que tenemos disponible en una partida, estas
letras son con las que deberemos formas las palabras
