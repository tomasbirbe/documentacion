# Next

## Que es compiling?

Compiling o tiempo de compilación, se refiere al proceso de tomar el código en un lenguaje y transformarlo en otro lenguaje o bien, en otra versión del mismo lenguaje

Un ejemplo puede ser cuando los desarrolladores usan TypeScript. A pesar de que es un lenguaje cómodo y seguro de utilizar, los navegadores no lo comprenden. 

Por esto mismo es que TypeScript se compila a una versión de JavaScript que sea soportada por la mayoría de los navegadores

![](./assets/compiling.png "compiling-process")

Este proceso ocurre durante la fase de desarrollo mientras editamos nuestro código como "preparación" para la fase de producción 

## Que es la minifying?

Los desarrolladores escriben código que sea fácil de leer para los humanos. El código puede contener información extra que no es necesaria para que el código funcione, como comentarios, espacios, identaciones y múltiples líneas

![](./assets/minifying.png "minifying-process")
El proceso de minifying un archivo es remover el código innecesario como el formateo y los comentarios sin cambiar la funcionalidad del código

El objetivo de este proceso es disminuir el peso de los archivos para mejorar el rendimiento

En NextJS, los archivos JavaScript y CSS son automaticamente minificados cuando el projecto esta en fase de produccion.

## Que es bundling?

Habitualmente los desarrolladores "rompen" la aplicacion en modulos, componentes y funciones ya que, si no fuese asi, las aplicaciones serian monolitos llenos de informacion y seria ininteligible.

![Image about bundling process](./assets/bundling.png "bundling-process")

## Que es code splitting?

Normalmente los desarrolladores dividen la aplicacion en distintas paginas que pueden ser accedidas por distintas urls. Cada una de estas forma un unico entry point a la aplicacion.

Code splitting es el proceso de separar el bundle de la aplicacion en "chunks" mas pequeños

![Image about code splitting process](./assets/code-splitting.png "code-splitting")

   
