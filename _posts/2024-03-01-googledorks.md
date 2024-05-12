---
layout: post
title:  "¿Que es el Google Hacking?, ¿Para que sirve?"
author: Pablo
categories: [ Cybersecutity, Dorks ]
image: assets/images/5.jpg
---

Sabes que día es hoy? Hoy es jueves de hilo, y en especial sobre el Google Hacking o Google Dorking. Veámoslo!!

🧵👇🏽

¿Y esto del Google Hacking que es? 🤔

Pues el Google Hacking o Google Dorking es una técnica, que emplea una búsqueda avanzada / filtros usando operadores que especifican una condición en el tradicional buscador de Google

¿Operadores, hay que sumar y restar? ➕➖

Nooo, los operadores son como "parámetros" de búsqueda, que nos permitirán acotar los resultados, cada uno tiene una función uno de ellos son, las comillas dobles, son operadores que sirven para buscar cadenas exactas, por ejemplo:

Figura 2 🖼️

Como veis, solo aparecen webs donde se menciona la palabra exacta. Pongamos otro ejemplo, si queremos buscar en la web del @INCIBE, entradas donde se mencione la palabra OSINT, utilizamos los siguientes operadores:

Figura 3 🖼️

En este caso, usamos el operador comillas dobles y el operador "site:" que realizará la búsqueda de la palabra en el sitio
Existen más de 40 operadores diferentes, aquí os dejo algunas cheat sheet:

🔗 https://sansorg.egnyte.com/dl/f4TCYNMgN6
🔗 https://cdn-cybersecurity.att.com/blog-content/GoogleHackingCheatSheet.pdf
🔗 https://afsh4ck.gitbook.io/ethical-hacking-cheatsheet/recopilacion-de-informacion/google-hacking/google-dorks

SANS Institute AT&T Cybersecurity @afsh4ck

¿Y esto que tiene que ver con la ciberseguridad? 🔓

Pues mucho, de hecho en auditorias de pentesting (red team). En el área, se suele utilizar para encontrar información privada indexada por el buscador. Por ejemplo, podríamos buscar el contenido del /etc/passwd para enumerar usuarios, añadiendo el operador "site:" para acotar la búsqueda

Figura 4 🖼️

Como veis, hay más de 2.500 sitios expuestos. Y no os hacéis una idea, de la de cosas que se pueden llegar a encontrar.
Os dejo por aquí, algunos filtros ya hechos para que los probeis:

🔗 https://github.com/Ishanoshada/GDorks
🔗 https://www.exploit-db.com/google-hacking-database

De hecho, muchas empresas, tienen tareas automatizadas para la recolección de los datos indexados, y tenerlos controlados.

ℹ️ https://github.com/IvanGlinkin/Fast-Google-Dorks-Scan