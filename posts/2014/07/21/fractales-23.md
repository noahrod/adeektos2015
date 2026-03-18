---
title: "Fractales 2/3"
date: 2014-07-21
author: Hrvoje Jaime Matosic
slug: fractales-23
---

Citando al post anterior sobre fractales: *En el siguiente post, veremos algunos ejemplos hechos en casa de fractales Julia, la explicación breve de cómo se hicieron y luego veremos un pequeño tutorial paso a paso para doblar un Julia con imágenes incluidas.*

En el post pasado, faltó mucha información para entender de dónde vienen los fractales. Los números existen en nuestra cabeza, podemos llegar a poner 17 manzanas sobre la mesa y poder llegar a decir de alguna forma extraña que contamos con un número 17 físico, pero ese número en realidad solo existe en nuestras mentes. Porque aunque haya 17 manzanas, el número 17 es un pensamiento. Es decir, el concepto del número es imaginario.

Podemos utilizar los números de muchas formas, por ejemplo podemos utilizar los números positivos para medir distancias, ya que las distancias no pueden ser negativas. Dicho de otra forma, no se puede llegar a decir que hemos avanzado -30m porque en realidad sí hemos avanzado algo, y eso ha sido 30m. Literal. Los números negativos nos sirven para hacer las cuentas del diario por ejemplo, saber cuánto hemos gastado y cuánto nos queda.

En cambio, si nos adentramos más, podremos descubrir que hay algo más aparte de los números positivos y negativos. Algo así como la teoría cuántica o el gato de Schrodinger, que puede estar vivo, muerto y/o vivo y muerto, es algo similar con los números imaginarios. Aquí es donde los números negativos pueden llegar a ser números negativos dentro de una raíz cuadrada y es obvio que empiezan a verse como números sin sentido para muchos.

Los números imaginarios, en conjunto con los demás sets de números se vuelven indispensables para la física cuántica. Estos números se llaman complejos. Son muy usados para describir los cambios en las olas del agua por ejemplo:

http://vimeo.com/89098980

Con el uso de estos números, Mandelbrot en los 70's pudo crear los primeros fractales que partían de f(z) = z^2 +** c**, donde **c** es un número complejo. Posteriormente Gaston Julia los estudió y dio vida a los fractales Julia. Ahora que contamos con toda esta información podemos adentrarnos más y entender la forma en la que representamos objetos 3D en un espacio 2D y que antes, durante o después imaginamos.

Haremos una pregunta importante para reflexionar, ¿Cómo representamos el corte de una manzana en un espacio 2D? Es decir, representar todas sus imperfecciones, la forma y tacto de su textura, el color de cada partícula que la compone, los poros que existen, todas sus formas, etc.

Es por esto que muchas de las gráficas que existen para representar números complejos se les debe de agregar un poco de imaginación para llegar al objetivo que se tenía pensado antes para representar. El objetivo es echar la imaginación a volar con los números complejos, debemos de jugar con la perspectiva para ver más allá.

https://www.youtube.com/watch?v=wC1jHHF_Wjo

*Perspectiva Inversa*

Ya que los fractales son desarrollados a partir de números, también podemos utilizar imágenes que añadiéndoles diferentes combinaciones de números con números existentes para después agregarles 'algo más' los cuales son los números complejos crearemos fractales a partir de la combinación de imágenes como lo son los siguientes ejemplos.

[caption id="attachment_2449" align="aligncenter" width="720"][![image: A partir de la iteración y recorte de dos imágenes de paisajes](http://adeektos.com/blog/wp-content/uploads/2014/07/frac3.jpg)](http://adeektos.com/blog/wp-content/uploads/2014/07/frac3.jpg) Fractal Morado. A partir de la iteración y recorte de dos imágenes de paisajes[/caption]

Disculpen la baja resolución de los dos siguientes:

[caption id="attachment_2448" align="aligncenter" width="720"][![image: Fractal Verde. ](http://adeektos.com/blog/wp-content/uploads/2014/07/frac2.jpg)](http://adeektos.com/blog/wp-content/uploads/2014/07/frac2.jpg) Fractal Verde. A partir de la iteración y recorte de dos imágenes de paisajes[/caption]

[caption id="attachment_2447" align="aligncenter" width="720"][![image: Fractal Azul.  A partir de la iteración y recorte de dos imágenes de paisajes](http://adeektos.com/blog/wp-content/uploads/2014/07/frac1.jpg)](http://adeektos.com/blog/wp-content/uploads/2014/07/frac1.jpg) Fractal Azul. A partir de la iteración y recorte de dos imágenes de paisajes[/caption]

Los fractales anteriores se hicieron con dos imágenes de paisajes, las cuales se recortaron muchísimas veces y después combinado con sets de la imagen similares, para después formar un fractal 3D. La explicación paso a paso para crear un fractal 3D no será explicada por el momento.

El siguiente vídeo muestra fractales Julia, cada segundo que pasa muestra etapas cada vez más detalladas de las formas de los Julia, las fórmulas para hacer este tipo de fractales fueron:

**z = z^2 + c, z = z^3 + c, z = z^5 + c, z = z^7 + c**

https://www.youtube.com/watch?v=7pfGmoWoXeQ

Los fractales Julia no son difíciles de hacer (veremos el proceso paso a paso en la última parte del artículo). Una vez que se ha entendido la forma en la que se desarrollan estos, la parte tediosa viene cuando se debe de posicionar la cámara en diferentes partes del plano X,Y para que siempre haya zonas de colores y esta misma no renderee las zonas negras. También se deben de juntar los cerca de 18,000 frames o cuadros para dividirlos en sets de 29.97 fps (cuadros por segundo) y posteriormente volver a renderear todo en un solo vídeo.

En el siguiente artículo veremos el proceso completo para crear un solo frame y llegar desde esto:

[caption id="attachment_2450" align="aligncenter" width="841"][![image: Imaginemos que la línea continúa hacia la derecha e izquierda indefinidamente](http://adeektos.com/blog/wp-content/uploads/2014/07/number-line.png)](http://adeektos.com/blog/wp-content/uploads/2014/07/number-line.png) Imaginemos que la línea continúa hacia la derecha e izquierda indefinidamente[/caption]

A esto:

[caption id="attachment_2451" align="aligncenter" width="1024"][![image: Función arbitraria que puede representarse como la suma infinita de números](http://adeektos.com/blog/wp-content/uploads/2014/07/juliaFrac_notMine.png)](http://adeektos.com/blog/wp-content/uploads/2014/07/juliaFrac_notMine.png) Función arbitraria que puede representarse como la suma infinita de números[/caption]

¿Qué combinación de colores te gustaría ver en el tutorial para el fractal Julia?
---

**Note about images**: This post originally contained images that are no longer available and will be replaced with similar images based on the context.

