# Criba de Eratóstenes

## Indice 
1. Hablemos de Eratóstenes
2. Teoría de cribas 
3. Criba de Eratóstenes
4. ¿Para qué sirve?

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
>La criba de Eratóstenes es un algoritmo que permite hallar todos los números primos menores que un número natural dado. Se forma una tabla con todos los números
naturales comprendidos entre 2 y **n**, y se van tachando los números que no son primos de la siguiente manera: Comenzando por el 2, se tachan todos sus múltiplos; 
comenzando de nuevo, cuando se encuentra un número entero que no ha sido tachado, ese número es declarado primo, y se procede a tachar todos sus múltiplos, así
sucesivamente.El proceso termina cuando el cuadrado del siguiente número confirmado como primo es mayor que **n**.
