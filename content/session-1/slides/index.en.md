---
outputs:
- Reveal
title: ¡Desarrolla paquetes!
hidden: true
layout: list
weight: 11
output: hugodown::md_document
countdown: true
rmd_hash: 2225c7fe53272723

---

# Desarrollo de paquetes

<div class="highlight">

</div>

<div class="highlight">

{{< figure src="132682.jpeg" alt="Bike in repair room" caption="Picture by [Alexander Dummer on Pexels](https://www.pexels.com/photo/black-road-bicycle-inside-room-132682/)." width="400" >}}

</div>

------------------------------------------------------------------------

## Mis credenciales de desarrollo de paquetes R

-   Editora voluntaria para [de Revisión de software por pares de rOpenSci](https://ropensci.org/es/software-review).

-   Mantenimiento de la [Guía de desarrollo de rOpenSci](https://devguide.ropensci.org/es/index.es.html).

-   Creé el [blog R-hub](https://blog.r-hub.io).

-   Libro [HTTP testing in R](https://books.ropensci.org/http-testing/) con Scott Chamberlain.

-   Participé en el desarrollo de varios paquetes.

## ¿Por qué desarrollar un paquete R?

La forma más fácil de compartir código/datos/plantillas R Markdown... con

-   te (en el futuro),

-   las personas que conoces,

-   y los personas que no conoces.

------------------------------------------------------------------------

## ¿Por qué aprender sobre el desarrollo de paquetes?

[Jon Calder](https://joncalder.co.za/) [explicó](https://github.com/iandurbach/datasci-fi/tree/master/docs/packages/slides)

-   Compartir código (y datos);

-   Para aprovechar las herramientas existentes;

-   Para contribuir a otros paquetes.

------------------------------------------------------------------------

## ¿Quién puede escribir un paquete? ¡TÚ!

Susan Johnston [preguntó](https://github.com/susjoh/fibonacci).

-   ¿Puedes abrir R o RStudio?

-   ¿Puedes instalar un paquete?

-   ¿Has escrito alguna vez una función en R?

-   ¿Podrías *aprender* a escribir una función en R?

**¡Puedes escribir un paquete en R!**

------------------------------------------------------------------------

## Recursos sobre funciones

-   [Materiales del tutorial R-Ladies East Lansing de Stephanie Kirmer](https://github.com/rladies-eastlansing/2021-rfunctions#writing-r-functions)

-   [Escribe tus propias funciones de R](https://stat545.com/functions-part1.html), curso stat 545 por Jenny Bryan y The STAT 545 TAs;

-   [Capítulo sobre funciones](https://r4ds.had.co.nz/functions.html) en el libro "R for Data Science" de Garrett Grolemund y Hadley Wickham;

-   [Charla "Fun with Functions](https://zealous-wiles-e22e83.netlify.app/talk/funwithfunctions/) por Kaylea Haynes, R-Ladies Manchester.

------------------------------------------------------------------------

## ¿Qué es un paquete?

> Para tener menos miedo, tienes que decirte a ti mismo que se trata simplemente de una carpeta organizada de forma constreñida.

[Traducción de una frase Sébastien Rochette](https://thinkr.fr/transformer-plusieurs-scripts-eparpilles-en-beau-package-r)

------------------------------------------------------------------------

## Automatización

{{< figure src="automate_meme.jpg" alt="Pequeño monstruo que dice automatizar todas las cosas"  caption="Imagen del meme por [Allie Brosh](https://en.wikipedia.org/wiki/Hyperbole_and_a_Half)"  >}}

------------------------------------------------------------------------

## Automatizar... ¿Cómo?

¿Te acuerdas de Clippy?

------------------------------------------------------------------------

## Automatizando... ¿Cómo?

Conoce un Clippy realmente útil, `{usethis}` ¡!

{{< figure src="https://usethis.r-lib.org/reference/figures/logo.png" alt="usa este logo, un robot"  >}}

------------------------------------------------------------------------

## ¿Por qué automatizar? Más fácil para...

Trabajo regular, enseñanza, reproducción de problemas.

<div class="highlight">

{{< figure src="5446296.jpeg" alt="Bike wheel with tools on the floor" caption="Picture by [cottonbro studio on Pexels](https://www.pexels.com/photo/wrench-on-a-ground-5446296/)." width="200" >}}

</div>

------------------------------------------------------------------------

## Objetivos para las tres sesiones

-   Conocer (las mejores :innocent:) herramientas para el desarrollo de paquetes;

-   Aprende que no hay magia, sólo práctica y :sparkles: consejos :sparkles:.

<div class="highlight">

{{< figure src="686230.jpeg" alt="Bike sign on a bike path, with tree leaves" caption="Picture by [Cristiana Raluca on Pexels](https://www.pexels.com/photo/white-bicycle-road-sign-686230/)." width="300" >}}

</div>

------------------------------------------------------------------------

## Visita al sitio web

:link: <https://rpkgdev-mechanics-2025.netlify.app/>

Diapositivas, notas de demostración, otros recursos

<div class="highlight">

{{< figure src="3932867.jpeg" alt="Small kid on a balance bike" caption="Picture by [Tatiana Syrikova on Pexels](https://www.pexels.com/photo/anonymous-kid-in-helmet-riding-run-bike-on-pavement-in-countryside-3932867/)." width="200" >}}

</div>

------------------------------------------------------------------------

## Hora del taller :bike:

Alternando entre ver y practicar en las salas de Zoom.

<div class="highlight">

{{< figure src="221237.jpeg" alt="Two bikes parked" caption="Picture by [Pixabay on Pexels](https://www.pexels.com/photo/two-bicycles-parked-upright-221237/)." width="200" >}}

</div>

------------------------------------------------------------------------

## De vuelta del taller

`{usethis}` para todo.

<div class="highlight">

{{< figure src="206040.jpeg" alt="Cycle path sign" caption="Picture by [Nika Dzamashvili on Pexels](https://www.pexels.com/photo/black-and-white-bicycle-road-sign-206040/)." width="400" >}}

</div>

------------------------------------------------------------------------

## `.Rprofile`

Como guardar los ajustes de una bicicleta.

¡No tendrás que ajustar la altura del sillín cada vez que salgas a dar una vuelta!

------------------------------------------------------------------------

## Dos ruedas siempre girando :bike:

-   Cargando, probando, editando.

-   Ejecutar (añadir) las pruebas, editar. En la próxima sesión!

------------------------------------------------------------------------

## Comprobación R CMD (devtools::check())

<div class="highlight">

{{< figure src="4543112.jpeg" alt="Bike traffic light" caption="Picture by [cottonbro studio on Pexels](https://www.pexels.com/photo/traffic-light-on-red-light-4543112/)." width="300" >}}

</div>

------------------------------------------------------------------------

## ¿Tienes preguntas?

¿Nos vemos en el próximo curso de desarrollo de paquetes?

Prepara las preguntas con antelación, envíalas con antelación si puedes.

<iframe src="https://giphy.com/embed/XFpCAWSfTwXh2uSEk2" width="480" height="269" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/moon-et-extra-terrestrial-XFpCAWSfTwXh2uSEk2">via GIPHY</a></p>

