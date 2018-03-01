A
---
layout: post
title:  "Sailfish OS, un año de uso después"
date:   2018-03-01 00:55:26 -0500
categories: hardware
tags: moviles, sailfish, linux
topimg: "img/aquafish.jpg"
thumb: "img/aquafish.jpg"
---

En Noviembre de 2016 cayó en mis manos mi primer equipo basado en Sailfish OS: Nada más y nada menos que un Intex Aquafish. De fabricacion hindú, este equipo lleva consigo el sistema operativo que varios buscaban como una alternativa que en verdad pudiera hacerle frente a las que dominan el mercado y que comprendan una alternativa que pueda utilizarse de manera regular. Aquí mis observaciones luego de un año como usuario del mencionado sistema.

#### La adquisición

Pasar a usar el Aquafish parecía una alternativa interesante y al parecer la más lógica luego de haber sido usuario de MeeGo Harmattan con el ya recordado Nokia N9 y además usuario tambien de Blackberry OS 10 sobre Blackberry Z30. Las tres plataformás antes mencionadas corrían una interfaz gráfica desarrollada sobre el famoso framework Qt, antes propiedad de Nokia y ahora de Digia.

Dos de los tres sistemás están basados en Linux (Blackberry OS utiliza QNX como base), los que también tienen partes de su sistema liberados bajo licencias libres, aúnque en la práctica los tres son propietarios. Finalmente tanto los desarrollos de MeeGo Harmattan como de Blackberry OS  fueron abandonados ya por sus respectivos fabricantes (Nokia tras la adopción de Windows en sus equipos y posterior compra por Microsoft y Blackberry tras adoptar Android). 

#### Generalidades sobre el equipo

Aquafish tiene un enfoque minimalista para mercados emergentes y eso se nota a primera vista. La cubierta de plástico que cubre su bateria se siente corriente al tacto. Intex vende este telefono sólo en un color: "Naranja coral". Una edición rebranded del mismo equipo, el Jolla C tiene una cubierta roja. sin embargo la posición de la cámara en ambos equipos imposibilita el intercambio de dichas tapas.

{% include image.html src="/img/2018-03-01-sailfish-un-anho-despues/foto_camara_aquafish.jpg" description="Fotografía tomada con la cámara del teléfono." %}

La batería tiene una duracion que puede ser útil si no se usan los datos móviles de forma exagerada (y teniendo inhabilitada la opción de GPS). La cámara por otro lado es una soberana porquería: una escasísima resolución y un acabado de imágenes mediocre. Desenfoca con facilidad, se nota que es un equipo barato y es lo que hay.

El equipo en cuestión es de doble chip. Sin embargo tiene ciertas limitaciones con el uso de 4G LTE, ya que no es compatible con bandas de frecuencia 900, así que si como yo eres usuario de Bitel, pues no lo aprovecharemos en este equipo.

El sonido es pobre. Su nivel de intensidad limitado. Escuchar audio de volumen bajo es materialmente imposible. Realizar llamadas en altavoz es una ironía, me obliga a llevarme el equipo al oído mientras hablo.

Aunque el Wifi tiene problemás con algunas redes N, va bien en G. El Bluetooth también va bien. No me dió problemás con unos audífonos Skullcandy que poseo aúnque no he probado con otros. 

#### Resistencia
Veamos, ya mencione que el equipo deja mucho que desear en cuanto a esto, y al tacto se siente "corriente". Plástico poco cuidado. La cubierta anaranjada ha empezado a decolorarse, además de haber sufrido algunos rayones bajo los cuales se percibe el color blanco del plástico base. El acabado es de tan poca calidad que de las letras plateadas que muestran el logotipo de la marca "Intex", se salió la "X" el tercer día de uso. Completamente inesperado.

Por otro lado, luego de un tiempo en mi bolsillo la camara de rompió. Así de simple. Se quebro la resina transparente que recubre la camara. Esto sólo ocasíona problemás al tomar fotografías con mucha luz.

#### El Sistema Operativo
En definitiva este es el apartado que más me interesa. Vamos a describirlo por puntos.
El sistema operativo Sailfish OS versión 2, utiliza una interfaz gráfica propia llamada "Silica", que como mencione líneas arriba está desarrollada con el framework Qt que se ejecuta sobre Wayland. Utiliza como base el proyecto MeR (MeeGo Reconstructed), por lo que su kernel es Linux y su gestor de paquetes Zypper.

{% include image.html src="/img/2018-03-01-sailfish-un-anho-despues/sailfish.png" description="Información del sistema operativo que devuelve el teléfono." %}

#### La interfaz de usuario
La GUI de Sailfish OS recuerda bastante a la de Nokia N9 MeeGo Harmattan. Las aplicaciones pueden ser cerradas haciendo _swipe_ de arriba hacia abajo y las aplicaciones aparecen yuxtapuestas mientras están minimizadas. 

#### La experiencia de usuario
No quería llegar a este punto porque es el más desfavorable para Sailfish OS. Primero, a alguien se le ocurrió que era práctico cambiar de tema o skin del equipo de forma rapida, mucho antes que habilitar e inhabilitar el Wifi o el Bluetooth. Para llegar a ese apartado es necesario hacer _swipe_ a la izquierda hasta llegar al hub de notificaciones y una vez allí, no hacer swipe de arriba hacia abajo, sino que presionar el lado superior de la pantalla hasta que se despliega el panel en cuestión desde donde puedo modificar las opciones antes mencionadas.

{% include image.html src="/img/2018-03-01-sailfish-un-anho-despues/hub1.png" description="Panel de Vista de Eventos (Events View)" %}

Como mencioné, alguien no tuvo mejor idea que colocar el selector de skins (que Sailfish OS llama pomposamente "Ambiences") al hacer swipe de arriba hacia abajo en cualquier caso. Desde este menú también se puede bloquear el equipo.

Algo que también resulta molesto por demás es lo que sucede al estar cerca el consumo total de la batería. El telefono emite un pitido insoportablemente molesto acompañado de una vibración que pareciera que tuviese como principal objetivo acabar cuanto antes con lo poco que queda de batería en el teléfono. Y de hecho eso es lo que sucede, ya que en una de esas advertencias entre vibración y ruido molesto el teléfono terminará por apagarse. Lo peor de todo es que no hay forma de modificar mediante las opciones este comportamiento. Al menos no por ahora.

{% include image.html src="/img/2018-03-01-sailfish-un-anho-despues/ambiences.png" description="Ambiences que aparecen a la mano en la interfaz." %}

Por cierto, no hay forma (al menos por ahora) de cambiar ni los fondos de pantalla ni las imagenes de bloqueo en este teléfono. Tienes que conformarte con las que trae el sistema por defecto. Algo bastante molesto.

Finalmente la forma en la que se maneja el cambio de horizontal a vertical de la pantalla al mover el teléfono en esas posiciones tiene una experiencia deficiente. Al hacer esto el teléfono vuelve su pantalla a negro y luego regresa a la pantalla cambiada. 

#### Las aplicaciones out-of-the-box
Este es otro apartado que quería comentar. Vamos por lo fundamental: La aplicación de teléfono. Digamos que usted recibe una llamada importante a cierta hora y no lo ha notado. Posteriormente la persona que lo llamó vuelve a llamarle y usted contesta. La persona le increpa el porqué de su no atención a su llamada. Usted revisa las llamadas que ocurrieron en el teléfono. Ni se esfuerce. Sailfish OS no guarda registro de ello. Sólo guarda esta información una vez y la última vez que ocurrió por cada diferente llamante. Lo cual por ejemplo me ha resultado poco práctico para demostrar que cierto banco me llamaba todos los dias a las 3 de tarde. En fin. Punto en contra.

Veamos algo también fundamental: El teclado. El teclado de Sailfish OS deja en definitiva mucho que desear. En comparación por ejemplo con teclados como el del Blackberry OS 10 que no sólo es predictivo (en cuanto a palabras) sino que el teclado era capaz de predecir que tecla en verdad intentabas presionar, aca no se da el caso. Las teclas están tan mal dispuestas y tienen un tamaño tan poco adecuado que oprimir la equivocada es muy fácil. En ese sentido es un verdadero dolor de cabeza cuando al querer oprimir la barra espaciadora termina uno oprimiendo puntos.

{% include image.html src="/img/2018-03-01-sailfish-un-anho-despues/teclado.png" description="El teclado por defecto en el teléfono. No encontré algún otro alternativo." %}

Un dato adicional sobre el teclado. Al igual que MeeGo Harmattan, Sailfish trae por defecto un emulador de Terminal para acceder a la línea de comandos del teléfono (lo cual es para mí bastante útil, sobre todo porque a veces se me antoja escribir mis entradas del blog desde la Terminal usando VIM que es mi editor favorito). El teclado de la Terminal en Sailfish OS es diferente, para incluir algunas teclas adicionales. Las teclas estan aún más juntas y son mucho más pequeñas. No tengo las manos de Slenderman, sino que mis dedos son más o menos torpes para una sección de espacio tan menuda, por lo que escribir allí me resulta poco práctico.

{% include image.html src="/img/2018-03-01-sailfish-un-anho-despues/tecladoT.png" description="Teclado del emulador de Terminal del teléfono." %}

La aplicación de Música tiene sus peculiaridades. La mejor forma de revisar las canciones es ir a la sección de "All Music". Para poder buscar una cancion hay que hacer un swipe incompleto desde la mitad de la pantalla hacia abajo, lo cual muestra un menu contextual desde el que se puede seleccionar "Search" para realizar la búsqueda. El problema con esto es que para poder hacer esta operación es necesario estar al comienzo de a lista, por lo que si de pronto estoy revisando la música y se me ocurre buscar alguna, debo ir primero a la que figure al comienzo para buscar la que quiero. Por otro lado, a alguien se le ocurrió que hay que preocuparse por la salud ótica, por lo que después de cierto tiempo de escuchar música a cierto volumen la aplicación te baja el volumen a la mitad y te muestra un mensaje de advertencia de uso. Eso es bastante tonto, para empezar porque la aplicacion de música no realiza normalización de volumen ni análisis sobre a que nivel de decibeles fue grabada la canción, por lo que a veces es preciso subir un poco el volumen. Esto es una copia carbón de la aplicación de música del Blackberry OS 10, que hace exactamente lo mismo y tiene la misma falencia, por lo que parece que Sailfish OS ha copiado algo que la verdad que no sirve.

{% include image.html src="/img/2018-03-01-sailfish-un-anho-despues/musica.png" description="Aplicación de música del teléfono." %}

Algo más sobre la aplicación de música en Sailfish OS ocurre con las notificaciones. Cuando digamos, llega un mensaje o un correo electrónico, o recibes una notificación en Twitter, el teléfono lanza una notificación sonora (que discorda incluso con el volumen de la música) que enmutece la música que está sonando, espera a que el sonido de la notificación termine y luego regresa a la música (la cual vuelve con cierto retraso por lo que parece que implementaron mal esto último). 

La aplicación de correo es otro problema. Es bastante impráctica. La navegación entre las carpetas de correo es poco intuitiva, si no me fijo en que en la parte superior de arriba hay un destello que me indica que hay algo a la derecha, no me doy cuenta de que se encuentran allí. Adicionalmente la búsqueda parece estar rota o mal implementada. Luego de hacer una primera búsqueda, al querer hacer una segunda, ocurre que al teclear un caracter, la caja de búsqueda pierde foco y muestra la búsqueda de un solo caracter. Es necesario volver a presionar sobre la caja de búsqueda para buscar el correo o cerrar y teclear el segundo caracter y nuevamente repetir lo anterior, así caracter por caracter para volver a hacer la búsqueda, en definitiva, un desarrollo poco cuidado.

Sobre la aplicación de Twitter tengo dos palabras: No existe. No hay aplicación de Twitter propiamente dicha. En su lugar hay un notificador que te indica sobre las menciones que te hicieron y que en el caso de ocurrir alguna te abre el browser para que puedas verla. Llama la atención que al equipo de Sailfish no se le haya ocurrido siquiera tomar alguna de las aplicaciones comunitarias existentes y mejorarla para tal fin. En su lugar, estoy utilizando Piepmatz, que no es muy buena, pero es lo que hay. La otra que sugieren, Tweetian, es demásíado limitada, no la recomiendo.

Finalmente quiero hablar del browser por defecto. El browser de Sailfish OS, a diferencia de lo que puede pensarse ya que esta escrito con Qt, utiliza Gecko (sí, el de Firefox, con todos los problemás que tiene) en lugar de WebKit o Blink como motor de renderizado. Con esto más de una vez se pueden notar problemás de renderizado en las páginas. Dicho sea de paso, la interfaz del mismo browser parece tener unos cuantos glitches que deberían corregir. A lo mejor con la salida de Firefox Quantum y el cambio a Servo como nuevo engine, ellos cambien a Gecko por este último. Sinceramente yo no se en qué estaban pensando cuando decidieron esto.

{% include image.html src="/img/2018-03-01-sailfish-un-anho-despues/browser1.png" description="El Browser de Sailfish OS y sus problemás de renderización." %}

{% include image.html src="/img/2018-03-01-sailfish-un-anho-despues/browser2.png" description="Glitches en el browser." %}

La tienda de aplicaciones es limitada. No la utilicen. En su lugar instalen Warehouse. Van a encontrar más variedad de software allí.

#### Soporte para aplicaciones Android
El soporte para Android que usa como corazón a AlienDalvik de Myriad Group es respetable para una buena cantidad de aplicaciones comunes. Aplicaciones como Firefox, Uber, VLC, KDE Connect van bastante bien. Las aplicaciones que requieren de notificaciones van bien en todo... excepto en las notificaciones. Si instalas WhatApp o Signal, pueden pasar HORAS hasta que notes un mensaje importante porque el puente para las notificaciones de Android hacia Sailfish OS parece tener todavía mucho por hacer, ya que éstas simplemente no funcionan. 

Por otro lado, las aplicaciones que requieran de un Android No Rooteado simplemente no funcionarán. Probé, Super Mario Run, Pokémon Go y Miitomo (de Nintendo). Ninguna de las tres funcionan. PuzzleFighter (de Capcom) parece no tener problemás. 

#### Sobre la comunidad
Depende. Si tienes dudas sobre el uso de Sailfish OS es probable recibir ayuda de comunidades de MeeGo o de Maemo. Los foros de ayuda de Jolla pueden demorar bastante en responderte. 

También hay fanboys que no admiten críticas (Como los de @jollaes, evítalos. Esa cuenta, por cierto no es oficial). Recomiendo no hacerles caso.

#### Conclusiones
Sailfish OS es un sistema operativo que aún tiene mucho pan por rebanar. Requiere no de un poco sino más bien de un mucho de trabajo en el que deben de revisar la experiencia de usuario y los bugs que aún tiene. Sin embargo, esta semana fue anunciado Sailfish OS 3 para el tercer cuarto de este año. Esperemos que todas estas falencias hayan sido superadas. Aun así y a pesar de todo, yo recomiendo Sailfish OS. Creo que es conveniente darle una oportunidad. Y si no eres partidario de usar Android o iOS es una buena alternativa. No es tan buena como Blackberry OS 10 o MeeGo Harmattan, pero esperemos que las mejoras estén por venir.

Nos vemos.
