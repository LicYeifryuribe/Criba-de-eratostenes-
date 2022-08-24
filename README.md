# Criba de Eratóstenes

## Indice 
1. Hablemos de Eratóstenes
2. Teoría de cribas 
3. Criba de Eratóstenes
4. ¿Cómo se aplica?
5. Numeros primos 
6. Pongamos en práctica
7. Bibliografia 

## Eratóstenes
>Eratóstenes de Cirene (Cirene, 276 a. C.-Alejandría, 194 a. C.) fue un matemático, astrónomo y geógrafo griego de origen
cirenaico. Concibió por primera vez la geografía como una disciplina sistemática, desarrollando una terminología que todavía se usa en la actualidad. 
Es conocido principalmente por ser la primera persona en calcular la circunferencia de la Tierra, lo que hizo al comparar las altitudes del Sol del mediodía en dos
lugares separados por una distancia norte-sur. Su cálculo fue notablemente preciso. También fue el primero en calcular la inclinación del eje de la Tierra (nuevamente 
con notable precisión). Además, pudo haber estimado la distancia desde la Tierra hasta el Sol e ideó intercalar cada cuatro años un día adicional en los calendarios,
produciendo el año bisiesto.Creó el primer mapa del mundo, incorporando paralelos y meridianos basados en el conocimiento geográfico disponible de su época.

## Teoría de cribas
>La teoría de cribas es un conjunto de técnicas generales en teoría de números, diseñadas para contar o estimar el tamaño de un conjunto de números enteros. El ejemplo
primordial de un conjunto tamizado es conjunto de números primos menores iguales a $x$. Correspodientemente, el ejemplo primordial es la criba de Eratóstenes, o más 
general, la criba de Legendre. El ataque directo sobre los números primos usando estos métodos muestra obstáculosaparentemente insuperables, en el camino de la
acumulación de términos de errores.
Un resultado exitoso es la aproximación de un conjunto tamizado en específico (por ejemplo, el conjunto de números primos) por otro conjunto simple (por ejemplo, el 
conjunto de los números casi primos), que suele ser un poco más grande que el conjunto original y más fácil de analizar. Cribas más sofisticadas no trabajan directamente
con el conjunto en si, sino que cuentan de acuerdo con funciones de peso cuidadosamente elegidas en el conjunto.

## Criba de Eratóstenes
>La criba de Eratóstenes es un algoritmo que permite hallar todos los números primos menores que un número natural dado. 

## ¿Cómo se aplica?
>Se forma una tabla con todos los números naturales comprendidos entre 2 y **n**, y se van tachando los números que no son primos de la siguiente manera:
Comenzando por el 2, se tachan todos sus múltiplos.Comenzando de nuevo, cuando se encuentra un número entero que no ha sido tachado, ese número es declarado primo,
y se procede a tachar todos sus múltiplos, así sucesivamente.El proceso termina cuando el cuadrado del siguiente número confirmado como primo es mayor que **n**; Una condición es que x²≤**n**.

## Numeros primos 
>En matemáticas, un número primo es un número natural mayor que 1 que tiene únicamente dos divisores positivos distintos: él mismo y el 1. Por el contrario, los números compuestos son los números naturales que tienen algún divisor natural aparte de sí mismos y del 1, y, por lo tanto, pueden factorizarse. El número 1, por convenio, no se considera ni primo ni compuesto.

## Pongamos en práctica 
>Encontrar los numeros primos del 2 al 40, usando la criba de Eratóstenes
![image](https://user-images.githubusercontent.com/112005825/186521381-8d148434-30e3-4e8c-a66c-47843032924a.png)
![image](https://user-images.githubusercontent.com/112005825/186521558-4d058cf2-d24e-477c-bfca-febc1db7677a.png)
![image](https://user-images.githubusercontent.com/112005825/186521634-d2842b4b-c1dd-4e09-b691-6519b9b9dd58.png)
![image](https://user-images.githubusercontent.com/112005825/186521680-97d53d69-7704-4c87-8dd3-f61193684349.png)
![image](https://user-images.githubusercontent.com/112005825/186521717-2a7192a3-03c2-47a7-a19e-435ae7f13741.png)

## Criba de Eratóstenes por medio de programación (smartphone)
![image](https://user-images.githubusercontent.com/112005825/186535778-6c2232aa-af4f-44e7-a41a-ebcd43df6a27.png)
![image](https://user-images.githubusercontent.com/112005825/186535797-b876dfcc-263a-4bd4-afa5-5c61d578dcd0.png)
![image](https://user-images.githubusercontent.com/112005825/186535815-9fa2ef36-6c2a-4477-b8f1-2c0bf849c14b.png)

## Bibliografía
>https://es.wikipedia.org/wiki/Criba_de_Erat%C3%B3stenes

>https://es.wikipedia.org/wiki/Teor%C3%ADa_de_cribas

>https://es.wikipedia.org/wiki/Erat%C3%B3stenes

>https://es.wikipedia.org/wiki/N%C3%BAmero_primo

>https://numerosprimos.org/criba-de-eratostenes/

>https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax

>https://play.google.com/store/apps/details?id=ru.iiec.pydroid3&hl=es&gl=US

![image](https://user-images.githubusercontent.com/112005825/186530156-8ec5c80d-06ac-44d9-acff-e7f38ea12dbf.png)
