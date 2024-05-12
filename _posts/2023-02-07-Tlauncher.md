---
layout: post
title:  "TLauncher, el anzuelo perfecto"
author: Pablo
categories: [ Software, Malware ]
image: assets/images/5.jpg
---

## Historia de Tlauncher

Hace un tiempo los foros de Reddit, Inc. se empezaron a llenar de la teoría de que el lanzador de Minecraft **gratuito** y conocido por casi todos los jugadores del terreno, llamado tlauncher, este a diferencia de otros lanzadores del famoso juego, **contiene un gran cargamento de malware** y sorpresas que a medida que estos usuarios iban descubriendo, menos ganas de jugar tenían. Esta teoría se fue extendiendo por las redes, foros de internet, youtube ... Y más usuarios se unían a la investigación. Por este tiempo algunos aficionados a la seguridad informática realizaron algunas pruebas para confirmar lo que todo el mundo hablaba, adjunto enlaces de los test que se realizaron en la plataforma de SandBox de malware llamada triage [https://tria.ge/](https://tria.ge/) (desarrollada por Hatching International B.V.) y que arrojaron los siguientes datos: [https://tria.ge/230203-mnnq2sed54](https://tria.ge/230203-mnnq2sed54), en este informe de la plataforma de SandBox se puede ver que la puntuación es de 10/10, si vemos los datos que nos arroja el informe, podemos observar que contiene o instala:

- Adware
- Backdoors
- Robo de credenciales y datos
- Genera #persistencia
- Ransomware
- Command and Control (En algunos casos)

También se ha descubierto que **reinstala algunas versiones infectadas de java**, por lo que ==a pesar de desinstalar el programa este queda instalado mediante varias técnicas de persistencia==, también se observa que modifica el registro del sistema, que es una parte muy delicada del equipo, ademas de insertar archivos en rutas protegidas como puede ser system32, ademas instala certificados raíz, que puede ayudar a la ejecución e instalación de futuro malware y por variar un poco deshabilita el administrador de tareas, entre otras muchas otras cosas que hacen que este sea el anzuelo perfecto para mucha gente, y que ya tendrá **infectados a millones de usuarios.**

## Recomendaciones:

1- Formateo completo del equipo
2- Cambio de todas las credenciales
3- Uso de 2MFA {Proximo Articulo}

Un saludo!!!

RRSS: [https://linktr.ee/nuofrwk](https://linktr.ee/nuofrwk)

