---
layout: post
title:  "Destapando una organizacion criminal de criptomonedas empleando OSINT"
author: Pablo
categories: [ Cybersecutity, Scams ]
image: assets/images/5.jpg
---

## Desmontando una organización criminal de criptomonedas.

Esta empresa se hace llamar EASTXCOIN, y me interesé un día que en TikTok ví que una chica promocionaba una codigo para ganar 3.000 € en bitcoin de manera sospechosamente sencilla. Por ello me lanze a analizar la web. Todo esto ya esta denunciado a los FFCCSE (Fuerzas y Cuerpos de Seguridad del Estado)

## Empresa

### Localización e Información General

Si buscamos en la web del gobierno de Australia donde se supone que esta localizada su oficina (esta supuestamente situada en un bloque “multiservicios”, por lo que no se sabe si se sitúa ahí o no):

![Captura1](/assets/imagee.png)

No sale nada acerca de ninguna empresa con ese nombre:

![Captura2](/assets/image-1.png)

### Creador

Según exponen en su web (https://eastxcoin.com/about), la compañía la funda un tal “Hank Weizen”,del cual encuentro su [twitter](https://twitter.com/heynky):

![Captura3](/assets/image-2.png)

Como se puede ver, trabaja en el mundo de las criptos, de hecho, pone que es ingeniero en una
compañía relacionada con Bitcoin, BNS, Smart Contracts y aplicaciones descentralizadas:

![Captura4](/assets/image-3.png)

Y no solo eso, si no que vive en PNW según su perfil, que corresponde al Noroeste del Pacífico:

![Captura5](/assets/image-4.png)

Y espera, porque encuentro su [Github](https://github.com/hstove), su [Snapchat](https://www.snapchat.com/add/heynky), una cuenta de [Medium](https://medium.com/@heynky), una de [YouTube](https://www.youtube.com/@HankStoever), una de [LinkedIn](https://www.linkedin.com/in/hankstoever/), otra de [Pinterest](https://www.pinterest.es/stankyhanky/), otra de [Flickr](https://www.flickr.com/photos/21565025%40N05), una más de [Quora](https://www.quora.com/profile/Hank-Stoever) y un Instagram que ya no existe:

![Cap6](/assets/image-5.png)

A través de su Github y su Instagram, averiguamos su segundo apellido, “Stoever”. Y si entramos a su LinkedIn la ciudad donde vive: Bellingham, Washington, Estados Unidos. Ah por cierto, también su fecha de cumpleaños (1 de febrero). Sin ahondar mucho, también vemos a su pareja y a el, en el Mount Si, el 6 de julio de 2014, adjunto foto del momento:

![Cap7](/assets/image-6.png)

Que Hank vaya a la montaña es muy recurrente, ya que es una de sus actividades favoritas.
Mediante su [Facebook](https://www.facebook.com/hank.stoever), encontramos información como: que es de Bethesda, que su padre es Henry
Stoever (no voy a profundizar en su padre, porque si no el reporte acaba siendo de 100 paginas), y que su madre es Glenn Stoever, que tiene una hermana llamada Kari Stoever, y otra que se llama Hannah Stoever.

## Web

### Dominio

Se encuentra información que nos puede hacer pensar que puede tratarse de una estafa, ya que el
dominio se registra en un muy corto plazo de tiempo (12/05/2023), cuestión que no contrasta con la versión que se expone en la web acerca de su recorrido (desde 2018 —> https://eastxcoin.com/about):

![Cap8](/assets/image-7.png)

Tampoco se verifica que la web ha sido creada con anterioridad, si miramos los certificados SSL de la web

![Cap9](/assets/image-8.png)

### SEO

Con respecto al SEO, esta web no esta nada posicionada, y creo que esta hecho adrede, ya que si
miramos acerca del trafico, no obtenemos ningún dato:

![Cap10](/assets/image-9.png)

### Certificados SSL

Con respecto al emisor, se trata del propio Google, cosa que no me hace sospechar, ya que hay
entidades que te proveen de un certificado en tan solo 5 minutos y sin mucha verificación a diferencia de Google:

![Cap11](/assets/image-10.png)

### Aspecto

El aspecto que tiene, esta muy bien, el CSS se lo han currado, pero el rendimiento no mucho:

![Cap12](/assets/image-11.png)

Además de que la consola esta llena de errores, ya que no puede contactar con la API de Binance:

![Cap13](/assets/image-12.png)

### Política

Bien, esta web funciona de la siguiente manera:
1. Obtienes un código a través de terceros
2. Te registras en la plataforma
3. Introduces el código y recibes 0.34 Bitcoins
4. Para sacar el dinero a una cartera externa, deber verificar tu cuenta

Hay algunas cosas raras en el proceso, como que los códigos te los encuentras a través de vídeos de cuentas falsas de TikTok, además, la verificación que se menciona en el ultimo paso, es algo inusual, ya que es necesario introducir 0.01 Bitcoin para poder ser verificado y sacar todo lo que tienes en tu cuenta. Estos son algunos ejemplos de cuentas falsas que tienen estos codigos:

![Cap13](/assets/image-13.png)

![Cap14](/assets/image-14.png)

![Cap15](/assets/image-15.png)

Como veis generalmente cumplen un perfil, todas tienen la descripción igual, con el mismo código, además todas ellas tienen varios vídeos mostrando como canjean el código. Esto es muy extraño, y no lo de que te den un código, porque según la web, esto funciona así:

![Cap16](/assets/image-16.png)

### Copias de Copias

Se trata de una cuenta que en su descripción tiene un código que tienen otras cuentas para la
plataforma de eastxcoin.com pero para otra llamada bitlyxe.com, incluso la descripción es de la
misma sintaxis. Procedo a mirar la web y me encuentro este regalito:
Efectivamente

![Cap17](/assets/image-17.png)