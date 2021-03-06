# FAQ

## ¿Por qué Gulp? o ¿Por qué no otro?

Mira la [presentación introductoria] para un resumen de cómo se originó gulp.

## ¿Es gulp o Gulp?

gulp siempre se escribe en minúscula. La única excepción es en el logo donde Gulp aparece en mayúsculas.

## ¿Dónde puedo encontrar una lista de plugins para gulp?

Los plugins de gulp siempre incluyen la palabra clave `gulpplugin`. [Busca gulp plugins][search-gulp-plugins] o [consulta todos los plugins][npm plugin search].

## Quiero hacer un plugin para gulp ¿Cómo empiezo?

Consulta la wiki [Crear un plugin] donde encontrarás una guía y un ejemplo que te pondrá en marcha.

## ¿Cómo saber si mi plugin hace demasiado?

Pregúntate:

1. ¿Está mi plugin haciendo algo que puede que otros plugins necesiten hacer también?
  - Si es así, considera llevar esa funcionalidad a otro plugin. [Comprueba si aún no existe en npm][npm plugin search].
1. ¿Está mi plugin haciendo dos cosas, completamente diferentes, dependiendo de alguna opción configurable?
  - Si es así, podría servir mejor a la comunidad si lo separas en dos plugins diferentes.
  - Si las dos funciones son diferentes, pero se relacionan, probablemente esté bien.

## ¿Cómo deben representarse los saltos de línea a la salida de un plugin?

Usa siempre `\n` para evitar problemas con diferentes sistemas operativos.

## ¿Dónde puedo ir para estar actualizado con gulp?

Las actualizaciones de gulp se pueden encontrar en los siguientes twitters:

- [@wearefractal](https://twitter.com/wearefractal)
- [@eschoff](https://twitter.com/eschoff)
- [@gulpjs](https://twitter.com/gulpjs)

## ¿Tiene gulp un canal IRC?

Sí, ven a chatear con nosotros en #gulpjs [Freenode]. 

[Crear un plugin]: writing-a-plugin/README.md
[presentación introductoria]: http://slid.es/contra/gulp
[Freenode]: http://freenode.net/
[search-gulp-plugins]: http://gulpjs.com/plugins/
[npm plugin search]: https://npmjs.org/browse/keyword/gulpplugin
