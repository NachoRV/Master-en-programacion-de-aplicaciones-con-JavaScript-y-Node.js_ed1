# Clase 5

### Ejercicios

**1 -** Diseña un algoritmo introducido un numero y pasarlo a número romanos.
- Esperamos que el número sea menor de 50

![numeros_romanos](https://eloviparo.files.wordpress.com/2009/09/numeros-romans.jpg?w=466&h=172)

```
	Proceso conversionRomana
		Escribir "Dame un número:"
		Leer numero
		
		numeroOriginal <- numero
		numeroRomano <- ""
		
		Si numero <= 50 & numero > 0 Entonces
			
				Mientras numero > 0 Hacer
					// Escribir "Numero: ", numero
					
					Si numero = 50 Entonces
						numeroRomano = "L"
						numero = 0
					Fin Si
					
					Si numero >= 40 & numero < 50 Entonces
						numeroRomano = numeroRomano + "XL"
						numero = numero - 40
					Fin Si
					
					Si numero >= 10 & numero < 40 Entonces
						numeroRomano = numeroRomano + "X"
						numero = numero - 10
					Fin Si	
					
					Si numero = 9 Entonces
						numeroRomano = numeroRomano + "IX"
						numero = numero - 9
					Fin Si		
					
					Si numero = 8 Entonces
						numeroRomano = numeroRomano + "VIII"
						numero = numero - 8
					Fin Si	
					
					Si numero = 7 Entonces
						numeroRomano = numeroRomano + "VII"
						numero = numero - 7
					Fin Si	
					
					Si numero = 6 Entonces
						numeroRomano = numeroRomano + "VI"
						numero = numero - 6
					Fin Si	
					
					Si numero = 5 Entonces
						numeroRomano = numeroRomano + "V"
						numero = numero - 5
					Fin Si	
					
					Si numero = 4 Entonces
						numeroRomano = numeroRomano + "IV"
						numero = numero -4
					Fin Si
					
					Si numero <= 3 & numero > 0 Entonces
						numeroRomano = numeroRomano + "I"
						numero = numero - 1
					Fin Si		
					
				Fin Mientras
				
				Escribir numeroOriginal " en números romanos es " numeroRomano
		Sino
			Escribir numeroOriginal " NO es un número valido (0-50)"
		Fin Si
		
	FinProceso
```

**2 -** Diseña un programa que nos confirme si un [año es bisiesto](https://es.wikipedia.org/wiki/A%C3%B1o_bisiesto) o no.
- Caracteristicas de un año bisiesto:
	- Tiene que ser divisible entre 4 y no tiene que ser divisible entre 100
	- O puede ser divisble entre 100 y entre 400
```
    // Tu solución
```

**3 -** Diseña un programa que imprima los numeros del 1 al 100.
```
    // Tu solución
```

**4 -** Diseña un programa que imprima los numeros del 100 al 0.
```
    // Tu solución
```

**5 -** Diseña un programa que imprima los numeros pares entre 0 y 100.
```
    // Tu solución
```

**6 -** Diseña un programa que imprima los números impares entre un número dado por el usuario y los siguientes 50 números.
```
    // Tu solución
```

**7 -** Diseña un programa que imprima la suma de los 50 primeros numeros pares y el total de números impares partiendo de un número dado por el usuario
```
    // Tu solución
```

**8 -** Diseña un programa que cuente las veces que aparece una determinada letra en una frase que introduciremos por teclado.
```
    // Tu solución
```

**9 -** Diseña un programa que simula el lanzamiento de una moneda al aire e imprimir si ha salido cara o cruz.
```
    // Tu solución
```

**10 -** Diseña un programa que  simula cien tiradas de dos dados y contar las veces que entre los dos suman 10.
```
    // Tu solución
```