---
title: Demo
weight: 3
output: hugodown::md_document
rmd_hash: 12575f75eedd6fd9

---

## Recordatorio de la última vez

Tenemos un paquete con una función.

------------------------------------------------------------------------

## Un *test*

-   `use_testthat()`.

-   `use_test("time")`: primero un *test* simple, luego un *snapshot test*, luego un *snapshot test* del error.

-   [`devtools::test()`](https://devtools.r-lib.org/reference/test.html) o botón.

-   [`devtools::check()`](https://devtools.r-lib.org/reference/check.html)

:eyes: [sitio de testthat](https://testthat.r-lib.org/)

------------------------------------------------------------------------

## Más *tests*

-   Utiliza [`withr::local_options()`](https://withr.r-lib.org/reference/with_options.html) en un *test*.

-   Mira la documentación de [`testthat::test_path()`](https://testthat.r-lib.org/reference/test_path.html).

-   Crea una función de ayuda en un archivo `tests/testthat/helper-bla.R` y utilízala en una *test*.

:eyes: [sitio de withr](https://withr.r-lib.org/)

:eyes: [Código y archivos de ayuda para tus *tests* testthat](https://blog.r-hub.io/2020/11/18/testthat-utility-belt/)

:toolbox: ¡repite los pasos!

------------------------------------------------------------------------

## GitHub Actions

-   [`usethis::use_github_action_check_standard()`](https://usethis.r-lib.org/reference/use_github_actions.html). `R CMD check` en la nube, diferentes sistemas operativos.

:eyes: [utiliza esta función para configurar las Acciones de GitHub](https://usethis.r-lib.org/reference/github_actions.html)

:toolbox: ¡Repite los pasos!

------------------------------------------------------------------------

