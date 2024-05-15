---
layout: post
title:  "¿Como gestionar un incidente de ransomware?"
author: Pablo
categories: [ Cybersecutity, Incidentes, Ransomware ]
image: assets/images/2024-05-13-Como-gestionar-incidentes-de-ransomware/[PREV]-Como-gestionar-incidentes-de-ransomware.jpg
---

En este caso, hablaremos sobre como gestionar el incidente una vez ya ha sucedido. Generalmente cuando un incidente tiene cierto grado de gravedad, significa que la empresa no ha seguido "buenas practicas" o no estaba preparada para un incidente (si quieres que haga un hilo sobre como prepararse ante un incidente dale apoyo a este).


Por cierto, es importante tener claro que yo apoyo la idea de no pagar por el desencriptado de los datos, puesto que:

- Los atacantes ya tienen los datos en sus manos y no lo borrarán aunque pages (borrar no es lo mismo que publicar)

- Los atacantes, viendo que estas dispuesto a pagar, pueden reintentar atacarte puesto que saben que tienes potencial económico y estas dispuesto a pagar

- Pagar no garantiza la recuperación o no publicación de la información

- Rescates realmente altos que hacen peligrar la estabilidad de la empresa económicamente

- Pagando, promovemos y financiamos este tipo de ataques y organizaciones criminales

De hecho, casi el 60% de las victimas pagó el rescate en 2021 y 2022

![Estadistica ransomware de kaspersky](/assets/images/2024-05-13-Como-gestionar-incidentes-de-ransomware/Estadisticas.png)
*Imágenes extraídas desde kaspersky.com

----

Cuando nos damos cuenta que ha sucedido un incidente de seguridad, lo primero es determinar el alcance del incidente, para ello debemos

1. Identificar la familia de ransomware mediante la nota de rescate, muestras de ficheros cifrados o análisis del punto de infección (phishing, fichero con macros..)

2. Obtener información técnica sobre las características de la infraestructura (diagrama de red, logs, listado de activos...)

3. Tener contexto del incidente (cuando se ha producido la infección, que equipos hay infectados, como se produjo la infección...)


Una vez tenemos claro todo esto, deberemos trabajar en la línea de actuación según marca nuestro plan de gestión ante incidentes (que deberemos de haber definido antes de que ocurra el incidente) y notificar el ciberincidente a los organismos necesarios (para ello deberemos saber previamente que activos han sido afectados por el incidente) como el INCIBE-CERT , CCN-CERT Centro Criptológico Nacional , Mando Conjunto del ciberespacio, Agencia Española de Protección de Datos - AEPD ...

----

Después de esto, será clave contener la amenaza (que no continue la propagación) y eliminar las conexiones con el atacante (servidores c2...) para poder parar el ataque, incluso reubicar un nuevo firewall en un punto estratégico de la red para analizar el trafico y obtener e identificar IOCs


En tercer lugar, identificaremos la familia de ransomware de la que se trata para poder mitigarla posteriormente. 
Podemos usar algunas de estas herramientas para identificarla:

1️⃣ https://www.nomoreransom.org/crypto-sheriff.php?lang=es

2️⃣ https://id-ransomware.malwarehunterteam.com/

3️⃣ https://id.provendata.com/

4️⃣ https://www.incibe.es/incibe-cert/blog/familias-ransomware-acciones-de-respuesta-y-recuperacion

Para mitigar la amenaza, podremos actualizar las políticas de las soluciones (firewall, edr, ips...) con los IOCs obtenidos anteriormente y actualizar los equipos antes de cambiar las credenciales de todo el dominio

----

Ahora toca la parte en la que algunos se llevan las manos a la cabeza porque las copias de seguridad estaban en el mismo sitio que los datos o simplemente no tenían copias de seguridad (abajo tenéis un breve hilo sobre copias de seguridad)

Se nos pueden presentar varios escenarios:

![Escenarios](/assets/images/2024-05-13-Como-gestionar-incidentes-de-ransomware/Escenarios.png)

*Recordad que después de la recuperación de los datos, hay que realizar un análisis y desinfección antes de la restauración completa

Antes de revisar la viabilidad de estos escenarios, se recomienda, realizar una tabla de control adicional y paralela a los activos afectados donde se indique: identificador, datos, impacto y el resultado del escenario

https://x.com/nuoframework/status/1768294375979684235

----

Como siempre digo "Prevenir es mejor que curar" por lo que te recomiendo realizar un plan de gestión ante incidentes y preparar el entorno para estos casos y ataques. Además te dejo aquí algunos enlaces de interés sobre información general de hilo para que puedas leer más sobre esto. Comentarios con feedback, me gustas y retuits me ayudan mucho a que esto llegue a más personas y por lo tanto a promover la concienciación en ciberseguridad, muchas gracias por haber leído hasta aquí!!



🔗 ENLACES DE INTERÉS:

https://www.ismsforum.es/ficheros/descargas/Guia%20gestion%20crisis%20ciberincidente.pdf

https://nvlpubs.nist.gov/nistpubs/ir/2022/NIST.IR.8374.spa.pdf

https://angeles.ccn-cert.cni.es/es/formacion-360/30-bp-21-gestion-de-incidentes-de-ransomware

https://www.cisa.gov/sites/default/files/2023-06/stopransomware_guide_final_es.pdf

https://www.ccn-cert.cni.es/es/informes/informes-ccn-cert-publicos/2877-ccn-cert-ia-11-18-medidas-de-seguridad-contra-ransomware/file?format=html

https://www.incibe.es/ciudadania/ayuda/ransomware

https://www.incibe.es/sites/default/files/contenidos/guias/doc/guia_ransomware.pdf

https://www.incibe.es/sites/default/files/contenidos/guias/doc/guia_nacional_notificacion_gestion_ciberincidentes.pdf
