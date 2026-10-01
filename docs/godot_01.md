# Primeros pasos con Godot

**Godot Engine** es un motor de videojuegos libre, gratuito y de código abierto (*open source*) diseñado para crear juegos tanto en *2D* como en *3D*, así como aplicaciones interactivas. En este documento veremos algunas de sus principales características y aprenderemos a descargarlo, instalarlo y ejecutarlo.

## 1. ¿Qué es un motor de videojuegos?

Imagina que para rodar una película tuvieras que fabricar la cámara, construir los focos y coser el vestuario desde cero. ¡Sería un trabajo enorme! En el mundo de los videojuegos pasa algo parecido: si tuviéramos que programar desde cero cómo cae un objeto por la gravedad, cómo se dibuja cada píxel en la pantalla o cómo se reproduce un sonido a través de los altavoces, tardaríamos meses antes de poder mover a nuestro personaje.

Un **motor de videojuegos** (*game engine*) es un programa que ya incluye todas esas herramientas básicas resueltas:

* **Motor de física**: calcula saltos, rebotes, aceleraciones, caídas por gravedad y choques (*colisiones*).
* **Motor gráfico (renderizado)**: dibuja en pantalla las imágenes, fondos, animaciones, luces y efectos.
* **Motor de audio**: reproduce música de fondo y efectos de sonido en el momento adecuado.
* **Control de entradas**: detecta cuándo el jugador pulsa una tecla, hace clic con el ratón o mueve el stick de un mando.

De esta manera, nosotros no tenemos que reinventar la rueda y podemos centrarnos en lo verdaderamente divertido: diseñar las reglas del juego, crear niveles y dar vida a nuestras ideas.

## 2. Principales características de Godot

Godot se ha convertido en una de las herramientas más populares del mundo, tanto para personas que quieren iniciarse en el desarrollo de videojuegos como para estudios independientes (*indies*). Títulos tan conocidos como *Brotato*, *Dome Keeper* o *Cassette Beasts* han sido desarrollados con este motor. Algunas de sus principales características son:

* Es **100% gratuito y libre (*Open Source*)**: a diferencia de otros motores comerciales populares (como Unity o Unreal Engine), es completamente gratis: no hay versiones de pago ("Pro"), ni suscripciones mensuales, ni limitaciones de uso. Tampoco añade logotipos ni marcas de agua obligatorias a tus juegos. Además, todo lo que crees es 100% tuyo. Si en el futuro decides publicar tu juego o venderlo, no tienes que pagarle porcentajes ni comisiones a nadie.
* **Ligero y portátil**: ocupa menos de 100 MB, y no necesita un proceso largo de instalación: es un único archivo ejecutable. Puedes llevarlo en un pendrive USB y abrirlo directamente sin necesidad de permisos de administrador. Además, funciona de forma muy fluida incluso en ordenadores portátiles modestos o antiguos.
* **Motor 2D dedicado y real**: muchos motores actuales son en realidad motores 3D que "fingen" el 2D colocando una cámara fija. Godot cuenta con un motor 2D dedicado, que trabaja con coordenadas de píxeles reales, lo que hace que crear juegos de plataformas, laberintos o naves sea mucho más intuitivo.
* **Sistema de nodos y escenas**: la forma en la que Godot organiza los elementos de un juego es muy visual y lógica: los diferentes elementos del juego se estructuran en **nodos** interconectados (dibujos, audios, etc), y un conjunto de nodos agrupados forma una **escena**. Por ejemplo, podemos crear una escena con los datos de un personaje (imagen, movimientos, etc), y reutilizarla tantas veces como queramos en el juego.
* **Programación con *GDScript***: para indicar al juego qué debe pasar cuando ocurre algo (por ejemplo: *"si el personaje toca una trampa, restar una vida"*), necesitamos programar. Godot utiliza principalmente *GDScript*, un lenguaje creado a medida para Godot, muy parecido a *Python*. Su sintaxis es clara, limpia y muy legible. Desde el propio editor de Godot podremos escribir cómodamente el código de nuestros videojuegos.
* **Multiplataforma**: podemos trabajar en Windows, Linux o Mac, y exportar el juego a distintas plataformas (PC, Android, web...)

## 3. Descarga e instalación

Para descargar Godot debemos ir a su [web oficial](https://godotengine.org/es/) y descargar la última versión para nuestro sistema operativo. Normalmente es un archivo comprimido y, al descomprimirlo, veremos un programa ejecutable que ya podremos lanzar.

En los siguientes documentos iremos aprendiendo a crear proyectos y añadir nuevas funcionalidades a nuestros juegos, a partir de proyectos sencillos que se irán complicando poco a poco.