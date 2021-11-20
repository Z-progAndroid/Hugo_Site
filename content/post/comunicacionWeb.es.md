---
title: COMUNICACION CLIENTE SERVIDOR
date: 
---

## PARTES QUE INTERVIENEN

### Lado del Servidor 
> **La programación del lado del servidor** es un procesamiento de una petición de un usuario mediante la interpretación de un script en el servidor web para generar dinámicamente páginas HTML como respuesta.
---
### Lado del Cliente
>**La programación del lado del cliente** es la manera que tienen las paginas web de gestinar eventos relizar peticiones al servidor y hacer validaciones simples y se integra en el codigo HTML
---
### Peticion Ajax
>  No es un lenguaje de programación sino una herramienta para comunicar el lado del cliente con el del servidor.
> 
> Permite realizar peticiones a tu servidor, sin necesidad de recargar la página. 
> 
> el lado del cliente, mediante AJAX, invoca un script del lado del servidor hecho para realizar dicha consulta.
> 
> Y el lado del cliente sigue respondiendo a los evventos haste que llega la informacion de la petición.
---
### HTML
>**HTML** es la base de la web. Si quieres construir una página mediante las etiquetas html se crea el cuerpo  de pagina web y luego mediante la el leguaje del lado cliente y servidor rellenas esa estrucutra

# Resumen del proceso de carga 
## GRAFICO 
![GRAFICO](http://3.bp.blogspot.com/-tcRImpq0phs/Vm8L2Z_HacI/AAAAAAAAExs/sAsD77cbIB4/s1600/ajax_process.gif)

>1. Se envía la solicictud al servidor. Este la recibe y comienza el proceso de construir la página web. Si existe código PHP, se ejecuta en este momento, se hacen todas las consultas a la Base de Datos. El resultado es una página con HTML y tal vez JavaScript.
>
>
>2. Tu navegador recibe la página, interpreta y usa el HTML para construirla. La tienes en pantalla.
>
>
>3. Mientras interactúas con la página, todo es procesado por Javascript. Interactúara contigo respondiendo a tus eventos, hasta que cierres la página.
>
>
>4. Si necesitas una consulta a la BD, para no cargar otra página, se puede utilizar la tecnología AJAX que permite a JavaScript mandar peticiones a scripts de PHP. Javascript recibe como respuesta cadenas de texto, y en base a la respuesta puede dibujar nuevos elementos de la interfaz gráfica o cambiarlos. Tienes una página interactiva.
