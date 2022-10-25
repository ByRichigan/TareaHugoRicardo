+++
archetype = " "
title = "Proceso Comunicacion"
weight = 3
+++

# Orden de Procesos en la Comunicación

## 1 Lenguaje de parte del Servidor PHP
Se envía la solicitud al servidor. El servidor la recibe y empieza a crear todo en base a lo recibido. Los fragmentos de codigo PHP se ejecutaran primero. Despues se hacen todas las consultas a la Base de Datos. El resultado es una página con HTML y tal vez JavaScript.
![ImagenProceso](/img/proceso.jpg "Tu imagen") 

## 2 Lenguaje HTML
El navegador recibe la página del proceso previamente mencionado, interpreta y usa el HTML para construirla.

## 3 JavaScript
A medida que se va construyendo la pagina web se va procesando todo el codigo JavaScript.

## 4 Conectar JavaScript y PHP
Finalmente necesitaremos un software que sea capaz de unir el JS con nuestro PHP. En resumen esto con el software adecuado nos permitiria realizar peticiiones al revidor sin necesidad de que la pagina sea recargada.

![ImagenURL](/img/url.png "Tu imagen") 







