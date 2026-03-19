---
title: "Motores de Juego"
date: 2014-06-30
author: Hrvoje Jaime Matosic
slug: motores-de-juego
---

Muchas veces, cuando uno empieza a escribir, investigar, desarrollar, leer y/o aprender sobre algo se da cuenta que hay muchísimas herramientas, documentación, ayuda, etc. sobre ese tema. Por ejemplo, para el desarrollo de vídeo juegos existen muchísimas herramientas.

Primero, hablaré un poco de la historia de los 'Game Engines' (GE) (Motores de juego). Los primeros GE comerciales llegaron en los 70's cuando también las primeras generaciones de consolas para vídeo juegos aparecieron, así como también las primeras computadoras personales. Rápidamente, los programadores pudieron desarrollar vídeo juegos sencillos, ya que el poder de procesamiento, el bajo costo del hardware y la baja expectativa de los usuarios daba para desarrollar vídeo juegos divertidos y relativamente rápidos de hacer. La siguiente liga tiene más de 200 juegos simulados en JAVA, que puedes jugar en tu explorador además de guarda tus puntuaciones y después te da la opción de retar a otros usuarios para obtener puntuaciones más altas : [InThe70s](http://www.inthe70s.com/games/)

Siguiendo con la historia de los GE, en el siglo 21, los equipos con mayor procesamiento y a veces con un coste mucho mayor, además de las aumentadas expectativas del usuario hicieron difícil que un único programador produjese un vídeo juego para consolas o computadoras. Además, la mayor parte de las compañías dueñas de las consolas, no permitían que programadores independientes desarrollaran juegos para estas.

La otra problemática era que para desarrollar un juego para las consolas, se necesitaba de una gran inversión de cerca de los 3 millones de dólares en el 2000 para después dispararse a los 20 millones en el 2010. Y, que aunque hubiera estudios que tuvieran esta cantidad de dinero, era muy riesgoso desarrollar algo que no daba garantía de que fuera bueno o incluso que las compañías de consolas rechazasen al juego para publicarlo. Obviamente, existía la WEB para que programadores independientes y pequeños estudios realizaran juegos divertidos, de bajo coste y rápidos. Seguramente, los que hayan nacido en los 80's y 90's recordarán algunas páginas que hosteaban juegos online, los cuales podías jugar en clase y en casi cualquier explorador que fuera compatible con FLASH.

La mayor parte de estos juegos estaba desarrollado en Javascript.

Algunas de estas páginas todavía existen, por ejemplo:

* [JuegosJuegos](http://www.juegosjuegos.com/)

* [Juegos](http://www.juegos.com/)

* [MiniJuegos](http://www.minijuegos.com/)

* [NewGrounds](http://www.newgrounds.com/)

* [TeaGames](http://www.teagames.com/) y muchas otras...

Todavía recuerdo, cuando bloqueaban estas páginas en la escuela, pero siempre encontrábamos la manera de llegar a ellas mediante un PROXY o pidiéndole al encargado de TI que desbloqueara las páginas por un momento.

Mucho después del boom de los juegos en la WEB, llegaron los móviles, que definitivamente han revolucionado la forma de jugar, hacer e inventar, sin menospreciar los largos tiempos de diversión, la calidad de juego, el arte y la frustración entre otras cosas que nos dan los juegos para consola y PC.

Volviendo al tema de las muchas herramientas que tenemos para realizar actividades cotidianas y no tan cotidianas, llegamos a las diferentes herramientas para desarrolladores independientes o Indie Developers en inglés (ID) que diferentes empresas recientemente han dejado que los ID usen, herramientas que, antes tanto cuidaban y guardaban en secreto.

Por ejemplo, [Unreal Engine](https://www.unrealengine.com) no hace mucho soltó un TechDemo, donde se puede apreciar la calidad de texturas, modelos, partículas y shaders, todo esto en un Nexus 5:

https://www.youtube.com/watch?v=GEFDegk_OTM

UE cuesta $19 dólares por mes, además de que debes compartir el 5% de tus ganancias netas, es decir, si el juego cuesta $10 dólares en el AppStore de iOS, la tienda quitará 30% por cada vez que alguien compre el juego, es decir habrá una ganancia de $7 dólares, pero antes de poder recoger los $7 dólares, un 5% de esos $7 dólares deberá ser restada. Los $7 dólares representan la ganancia neta, para que al final un total de $0.35 dólares sea restada de este total, dando como resultado $6.65 dólares. El 5% de tus ganancias netas no parecen mucho, pero multipliquen esta cantidad por un millón de descargar y ahí es cuando el peso se empieza a sentir.

Otro de los obstáculos que veo para los ID es que para que el GE de UE corra en tu ordenador de una forma decente, como requerimientos recomendados se pide Quad-core Intel o AMD de 2.5Ghz, una tarjeta de vídeo Nvidia 470 GTX o AMD similar y por último 8GB en RAM.

Siendo sinceros, en México hay muy pocos desarrolladores que cuentan con máquinas con capacidades de este tipo.

Tuve la oportunidad de probar UE en una VAIO con i5 y Nvidia de 1GB[ (Aquí el Link) ](http://www.game-debate.com/laptop/index.php?la_id=789&laptop=Sony%20Vaio%20SVF1421C5E%20(Intel%20CoreTM%20i5%20+%20Nvidia%201GB))y el engine se sentía tonto.

Por último, para programar en UE se necesita conocimiento de C++, debo admitir que es un lenguaje hermoso en todos los sentidos, pero se debe tener mucho cuidado ya que usándolo es donde se puede realmente echar a perder un juego, donde constantemente se tienen cuellos de botella en la memoria y esta debe ser limpiada.

[GameMaker](https://www.yoyogames.com/studio/buy) es otra opción para desarrollar para móviles, es gratis con ciertas restricciones como el splash screen el inicio, pero ofrece facilidad para hacer juegos. Usa una interfaz usuario o user interface (UI) en inglés para mover, arrastrar y soltar elementos para hacer tu juego. Tiene soporte para Android y HTML5. Hay otra versión de $99 dólares y otra de $799, creo que los precios para los ID son muy accesibles.

En México, existen algunas empresas que usan esta herramienta.

GameMaker no tiene desventajas grandes, aunque muchos desarrolladores estarán inconformes con la forma en que se realizan los juegos en esta plataforma, y es que muchos dicen que arrastrar, soltar, mover y combinar elementos no es programar. No he usado mucho GameMaker para darle un veredicto bueno o malo, pero soy de la idea de que si la herramienta sirve para hacer lo que tengas en mente, no hay necesidad de romperse la cabeza con otras herramientas.

Juego hecho con GameMaker

https://www.youtube.com/watch?v=t6VMqqBu6Hk

Por último, hablaré de Unity siendo la fuerte competencia de UE. Esta, es la herramienta con la que más he trabajado y también una de las primeras con las que empecé. Fácil de aprender, con una interfaz muy limpia y una curva de aprendizaje muy corta al principio.

Showcase 2013

https://www.youtube.com/watch?v=rYBaZyqiYZo

Existe una versión gratis, que goza de muchas características como lo son exportar a iOS, Android, Windows Phone e incluso Blackberry para los móviles. La versión de paga, incluye características muy buenas que deben tomarse a consideración dependiendo de lo que se quiera alcanzar. Opino que las características de la versión de paga no son necesarias si se quiere desarrollar para móviles. Se puede pagar la versión completa perpetua, o bien pagar por mes y obtener todas las actualizaciones disponibles mientras se mantengan los pagos. Son $75 dólares por mes o $1,500 dólares de la versión perpetua. Si se es estudiante, se pueden conseguir versiones perpetuas a mitad de precio.

El vídeo pasado, fue el ShowCase del 2013, pero les recomiendo que vean el siguiente vídeo para darse una idea del potencial que tiene la siguiente versión de Unity, es decir Unity 5. Promete mejores shaders, iluminación en tiempo real mejorada, mejor audio, el hermoso [WEB GL](http://adeektos.com/blog/webgl-y-sabemos-para-donde/) editor de 64 (algo que ya es necesario para los proyectos, que ya están pesando 7GB o más y que fácilmente escalarán), promoción de apps sin la necesidad de un ThirdParty, y otras características importantes.

https://www.youtube.com/watch?v=dk8gpz0o5TU

La programación es en Boo, C# o UniScript que es una combinación entre C# y Javascript. Sé que hay algunas otras herramientas como Construct2, GameSalad, GameEditor, Styncyl entre otras, las cuales desconozco su uso.

¿Qué herramientas para hacer vídeo juegos conoces? ¿Cuál crees que es la mejor?
