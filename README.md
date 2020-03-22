# ClubProgramacion Ejercicios

1.	Realiza un programa que realice la siguiente serie. Solo debes tener un solo método que retorne un String con la serie solicitada y su parámetro sea un número entero positivo. Si
el número no es positivo, solo retorna el número.
        Entrada: 22
        Salida: 22 11 34 17 52 26 13 40 20 10 5 16 8 4 2 1

        Entrada: -22
        Salida: -22 

2.	Realizar un programa que contenga un método que su parámetro sea una cadena de números enteros, y que realice la suma de todos los números de un solo dígito que se puedan extraer del número dado, la suma ahora será el número a abstraer dígitos, repetir hasta obtener un número de un solo digito y retornarlo.
  
        Entrada: 155
        suma = 1 + 5 + 5 = 11 (no es de un digito)
        suma = 1 +1 = 2 (si es de un digito)
        Salida: 2

3.	Realice el método que te permita obtener la diferencia entre 2 números introducidos por la misma línea y separados únicamente por un espacio. Restricciones: Usar solo el método length() y charAt() de String.

        Entrada: 100 200
        Salida: 100

	Entrada: 16 12
	Salida: 4

4.	Dado un número, ordenarlos de manera ascendente y descendente, restar el número ascendente al número descendente repitiendo la operación hasta que el resultado dado sea cero o bien ya haya sido obtenido con anterioridad
        
	Entrada: 444
        444 – 444 = 0
        0 – 0 = 0
        Salida: 2

        Entrada: 1234
        4321 – 1234 = 3087
        8730 – 0378 = 8362
        8632 – 2368 = 6174
        7641 – 1467 = 6174  
        Salida: 4

5.	En un arreglo de números, buscar las posiciones en las que se encuentra un número dado y agregarlas a un arreglo. Usar recursividad. 

        Entrada: [1	2	3	3	3	4	5	6	6	2]
        
        Salida: Para el número 3: [2,3,4]

6.	Escriba un programa que invierta las palabras en una frase mientras conserva el orden de las palabras mismas. Realizar de forma recursiva.

        Entrada: I love you.
        Salida: i evol .uoy

7.	Dada una serie de números, buscar la suma del número posición 0 a partir de los demás. Considerando la regla de la conmutatividad.
        
        Entrada: 10	3	2	7	8	1
        Salida:
                3 + 7
                2 + 8
                7 + 2 + 1
