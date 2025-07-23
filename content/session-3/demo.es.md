---
title: Demo
weight: 3
output: hugodown::md_document
rmd_hash: 22c4c00465157c32

---

## Recordatorio

Tenemos un paquete con una función y *tests*.

Esa función tiene una página de manual local.

## Documentación

:warning: rmarkdown y pkgdown necesitan que tu paquete sea *instalado*.

-   `install.packages("rmarkdown")`, [`usethis::use_readme_rmd()`](https://usethis.r-lib.org/reference/use_readme_rmd.html), escribir cosas, [`devtools::build_readme()`](https://devtools.r-lib.org/reference/build_rmd.html), commit+push, mirar el repositorio de GitHub.

-   `usethis::use_vignette("minipkg")`, escribe cosas. Viñeta != artículo.

-   `install.packages("pkgdown")`, [`usethis::use_pkgdown()`](https://usethis.r-lib.org/reference/use_pkgdown.html), [`pkgdown::build_site()`](https://pkgdown.r-lib.org/reference/build_site.html). Localmente.

:ojos: [pkgdown sitio web](https://pkgdown.r-lib.org/)

:toolbox: ¡Repite los pasos!

## Construir el sitio web automáticamente

-   `usethis::use_github_action("pkgdown")` cambia la configuración de las páginas GitHub del repositorio, añade la URL a la configuración pkgdown y a DESCRIPTION.

:ojos: [usa esta función para configurar las Acciones de GitHub](https://usethis.r-lib.org/reference/github_actions.html)

:toolbox: ¡Repite los pasos!

------------------------------------------------------------------------

