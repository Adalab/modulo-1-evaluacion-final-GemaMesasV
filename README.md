# Readme sobre mi proyecto de evaluación final del módulo 1

¡Hola profes! 

Este es el repositorio de mi proyecto para la evaluación final del módulo 1.

He de decir que han sido unos días muy intensos trabajando en él pero me siento muy orgullosa de haber podido terminarlo.

**Me gustaría explicar en este readme los diferentes apartado del código para que podais consultarlo si lo necesitais:**

El código está hecho con el *Adalab Web Started Kit*, al que le he borrado la información de ejemplo con la que venía y le he añadido la mía propia.

Mi proyecto se divide en:
1.  HTML
2. SCSS
3. IMAGES

En *src* vereis que el apartado de html y el de scss se divide en varias carpetas con lo que llamamos *partials* , que son las diferentes partes en las que se ha dividido el proyecto.

Por un lado tenemos **index.html** y **main.scss** en la raiz de la carpeta que son los archivos donde convergen los diferentes partials que he ido creando de forma que se conectan todos con el archivo principal, el cual es el que finalmente es mostrado cuando se inicia el proyecto.

Respecto al html, he hecho la división de la siguiente forma:
+ header
+ main
    + hero
    + sub-hero
    + free-shipping
	+ catalog
+ footer

El motivo por el que elegí esta disposición fue por identificar varias sub-partes en el main que podían hacer más sencillo el trabajo si se mantenían separadas unas de otras.

Por otro lado, en scss decidí hacerlo respetando los nombres que había dado previamente en html a las secciones para que quedara más claro:
+ core
    + reset
    + variables
+ layout
    + header
    + main-hero
	+ main-sub-hero
	+ free-shipping-section
	+ catalog
	+ footer
+ pages
    + index

Para la maquetación he seguido el diseño dado en Zeplin y los criterios del ejercicio de evaluación. Es por eso que me gustaría detallar las decisiones que he tomado durante el proyecto:
- El header es solamente el menú de navegación, en versión hamburguesa para móvil y tablet y completo para escritorio.

- El logo de Open Spaces inicialmente estaba en header, aunque lo moví a main -> main-hero por motivos de diseño, ya que quise hacer que sólo el menú de navegación fuera el que se mantuviera fijo a la hora de hacer scroll por la página.

- El primer módulo (Disfruta creando espacios): está maquetado con flexbox.
- El segundo módulo (Volverse organizado se siente mejor con Open Spaces) está maquetado con CSS Grid .
- El tercer módulo (Envío gratis garantizado) está maquetado con flexbox.
- El cuarto módulo(Disfruta creando espacios) está maquetado con flexbox.
- El quinto módulo (footer) está maquetado con flexbox.

- He cambiado detalles menores para personalizar mi proyecto:
  - Añadida la moneda ficticia "simoleones" en el texto " Envío gratis en compras desde 100" del tercer módulo.
  - Añadidos enlaces a youtube con diferentes canciones en los diferentes botones/enlaces del proyecto excepto en los textos de la columna "NOSOTROS" y "TIENDA", los cuales son enlaces a la página de Adalab, tal y como se pide en el enunciado.
  
Me encantará conocer vuestro feedback sobre mi proyecto. Me he divertido peleándome con el código y espero que os guste :)

¡Que tengais un buen día!
