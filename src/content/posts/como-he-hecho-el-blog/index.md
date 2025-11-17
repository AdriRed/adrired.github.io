---
title: Cómo he creado el blog
published: 2025-11-17
description: "Cómo coj**** se crea un blog de cero y alojado en un dominio???"
image: "./cover.png"
tags: ["Blogging", "Internet"]
category: Informática
draft: false
---

La verdad, nunca he tenido muchas intenciones de tener mi propia web, ni siquiera un blog! Pero me dió a pensar que tal vez es una forma de forzarme a hacer cosas y tener mini-proyectos para enseñarlo a los 4 gatos que os he compartido esta web.

En toda web alojada hace falta lo siguiente:
- Un dominio
- Un código
- Un sitio donde tener alojada la web

## El dominio

Mi búsqueda de dominios empezó hace tiempo, pero solo por diversión. Mi _nickname_ es adrired (Adrià -> Adri, Rojo -> red, por si no te habías dado cuenta lol) y llegué a pensar si podía integrar la extensión (el `.com` o `.es`) en mi nombre y formarlo con el dominio+extensión.

En este caso aprendí de las extensiones dominio de colores: `.red`, `.blue`, `.white`, etc... En realidad hay una barbaridad de extensiones de dominios, con una lista extensa [aquí](https://en.wikipedia.org/wiki/List_of_English-language_generic_Internet_top-level_domains).

Habiéndome dado cuenta de que podía formar `adri.red`, Martí me hizo una búsqueda rápida en distintos sitios de ventas de dominios y vio que estaba libre por unos 8€ (que el año que viene sube a 15€), pero eso fué hace unos cuantos meses, cuando él estaba subido en la burbuja del `.com` en 2025.

Con el dominio comprado, todo ya estaba en marcha.

Faltaba tener una web donde poder gestionar el dominio y aquí entra Cloudflare, donde puedo configurar un subdominio (blog.adri.red).

## El código

Sobre cómo crear un blog hay mil tutoriales. Yo quería una gestión fácil y sin matarme, y sin tener que pagar ni aprender mucha tecnología nueva.

Hay distintas tecnologías: Jekyll, Gatsby, Wordpress, Astro, una web en HTML puro y duro... Y me decanté por Astro, por las siguientes razones:

- Es una tecnología moderna (solamente esto mata a Wordpress y Jekyll)
- Ya sabía React y tiene una sintaxis parecida
- Tiene una gestión de entradas del blog por ficheros Markdown
- Produce una web estática
- Permite utilizar plantillas

## El alojamiento

Aquí entramos en terreno pantanoso, porque tenía muchas ideas: una máquina física, pagar por un servidor, etc...

La máquina física es una buena opción si hacer _tunelling_, ya que exponer tu máquina junto a tu red al internet abriendo puertos puede llegar a ser peligroso. 

El _tunelling_ usando Cloudflare se podría llegar a hacer, exponiendo únicamente una parte de la máquina (la que contiene la web). Pero esto iba a funcionar debido a que la plataforma de Cloudflare está en litigios con _LaLiga_ (gracias Tebas), y los fines de semana cuando hay futbol dejaría de funcionar por la puta cara.

Entonces pensé que se podía alojar en Github Pages. La únca pega es que el código de la web será visible... Pero qué más da!! Queremos hacer las cosas fáciles, no bien. Esto implica que también se puede acceder a mi blog desde [adrired.github.io](http://adrired.github.io/), y este redirige a la web que estás leyendo (blog.adri.red).

La web la he conseguido desplegar usando la [guia oficial de Astro para ello](https://docs.astro.build/en/guides/deploy/github/#how-to-deploy).

## Próximos pasos

Esto ya me sirve como plataforma para enseñar mis cosas, pero puede ser que un proyecto sera renovar el blog o hacer pequeños cambios a la template y customizarla al máximo.





