---
title: "Fractales, fractales, fractales"
date: 2014-07-14
author: Hrvoje Jaime Matosic
slug: fractales-fractales-fractales
---

**Serie 1, Post 1/3**

**Este es un experimento, el artículo se repartirá en 3 posts, cada uno por semana**

/**/

Hace unos días, estaba leyendo sobre la sucesión de Fibonacci, la cual es la sucesión de números naturales infinita, comienza con los números 1 y 1^1, después se suman los dos últimos números. Es decir, 1,1,2,3,5,8 y así sucesivamente. El resultado gráfico es una curva que se desarrolla de manera exponencial y que agregando ciertos parámetros y variables, podríamos editarla para que se pareciese a una curva en forma de caracol, o mejor todavía, a un fractal.

La sucesión de números de Fibonacci tiene aplicaciones en ciencias de computación, matemáticas y teoría de juegos, pero también se ve aplicado en la naturaleza, como en las hojas de los árboles, algunas flores, la col romanescu, el caparazón de los caracoles, los tornados, etc.

[caption id="attachment_2388" align="alignnone" width="1024"][![image: Ejemplo Sucesión de Fibonacci](http://adeektos.com/blog/wp-content/uploads/2014/07/macro-sunflower.jpg)](http://adeektos.com/blog/wp-content/uploads/2014/07/macro-sunflower.jpg) Ejemplo Sucesión de Fibonacci[/caption]

Un ejemplo de uso con la sucesión de Fibonacci en la computación, es la práctica de la recursividad, que a la larga el algoritmo que se usa es bastante ineficiente, pero eso ya es otra historia.

Me desviaré un poco de la sucesión de Fibonacci y explicaré un poco lo que son los fractales, la palabra fractal significa fracturado y se encuentra al igual que la sucesión de Fibonacci en muchas estructuras naturales, un ejemplo muy claro es el de la col romanescu, me recomendaron un lugar para ir a comerla en el D.F.: [http://cafezena.com/](http://cafezena.com/)

Debemos de tomar en cuenta dos puntos importantes en la definición de un fractal. La primera es: Es demasiado irregular para ser descrito en término geométricos tradicionales y la segunda es: Su forma está hecha de copias más pequeñas de la misma figura.

Podemos concluir, que un fractal es un objeto geométrico que se repite una y otra vez de forma (muy posible) infinita a diferentes escalas. Por lo tanto, podríamos llegar a vincular la sucesión de Fibonacci con la teoría de los fractales, ya que si recordamos en algún párrafo de arriba, sabemos que la sucesión de Fibonacci si se edita de manera correcta puede asimilar gráficamente la forma de un caracol y por lo tanto repetirse infinitamente hasta llegar al punto de tener propiedades similares a las de un fractal.

[![image: Spiral Fibonacci](http://adeektos.com/blog/wp-content/uploads/2014/07/fibonacci_spiral_fractal___extra_whirly_endo_by_randomness65535-d61kw5r-300x243.jpg)](http://adeektos.com/blog/wp-content/uploads/2014/07/fibonacci_spiral_fractal___extra_whirly_endo_by_randomness65535-d61kw5r.jpg)

Existen algunos tipos de fractales pero infinidad de opciones que se pueden realizar para obtenerlos. Por ejemplo existen los de tipo Mandelbrot, Kleinianos, Newtonianos, Hiper-complejos (donde ya parten de un objeto 3D) y algunos otros más. Pido disculpas si por alguna razón no escribí bien alguno de estos. Un ejemplo de un fractal hiper-complejo o también llamado fractal 3D:

![image: 3Dfractal](http://adeektos.com/blog/wp-content/uploads/2014/07/fractal3d-1024x1024.jpg)

 

No debemos dejar atrás o con menor importancia los ejemplos clásicos que dieron vida a todos los demás ejemplos que conocemos ahora. En 1872 apareció la función de Weierstrass, que es una función continua pero no diferenciable en ningún punto. Después surgieron otros ejemplos, que partían de una figura geométrica para posteriormente irse replicando, en las partes que llamaremos ramas y formar un fractal.

[![image: FracGif](http://adeektos.com/blog/wp-content/uploads/2014/07/Fractal1.gif)](http://adeektos.com/blog/wp-content/uploads/2014/07/Fractal1.gif)

 

Desgraciadamente, estos conjuntos fueron olvidados ya que eran vistos como objetos artificiales (no entiendo el sentido de que algo artificial pueda no ser interesante). Posteriormente, en los años 20's surgen otro tipo de fractales con funciones holomorfas, las cuales son el principal objeto de estudio del análisis complejo; son funciones que se definen sobre un subconjunto abierto del plano complejo **C** y con valores en C, que además de todo esto son complejo-diferenciables en cada uno de sus puntos. Es decir, puede ser infinitamente diferenciable y puede ser descrita mediante su serie de Taylor.

Dicho de otra forma, las funciones holomorfas podrían definirse (en un caso burdo y rápido) como una representación de una función como una suma infinita de términos. El típico: a1 + a2 + a3 + a4... a^n...

Quiere decir que, las funciones holomorfas pueden representarse gráficamente como fractales. Una función holomorfa se define como: [![image: holomorfas1](http://adeektos.com/blog/wp-content/uploads/2014/07/holomorfas1.png)](http://adeektos.com/blog/wp-content/uploads/2014/07/holomorfas1.png)

Aquí y con esta función se definen también los conjuntos de Julia, este tipo de algoritmos se representan con distintos colores, los cuales se colorean cuando cada pixel hace un número de iteraciones para 'escapar', ya que al aplicar sucesivas veces una función polinómica es muy posible que el resultado tienda a infinito. El conjunto de valores que no escapan al infinito mediante este tipo de operaciones son aquellos valores que se les denomina conjunto de Julia relleno, y a la frontera conjunto de Julia.

Es una simple función cuadrática con la que se pueden realizar los fractales de Julia. Función:  [![image: julia](http://adeektos.com/blog/wp-content/uploads/2014/07/julia.png)](http://adeektos.com/blog/wp-content/uploads/2014/07/julia.png)

[![image: juliaFrac](http://adeektos.com/blog/wp-content/uploads/2014/07/juliaFrac-1024x768.png)](http://adeektos.com/blog/wp-content/uploads/2014/07/juliaFrac.png)

 

La imagen de arriba representa un conjunto de Mandelbrot asociado a la familia de conjuntos de Julia.

En el siguiente post, veremos algunos ejemplos hechos en casa de fractales Julia, la explicación breve de cómo se hicieron y luego veremos un pequeño tutorial paso a paso para doblar un Julia con imágenes incluidas.
---

**Note about images**: This post originally contained images that are no longer available and will be replaced with similar images based on the context.

