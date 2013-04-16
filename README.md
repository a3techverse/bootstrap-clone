# [BAStrap v0.5](http://gcba.github.com/BAstrap)

BAStrap es el framework del Gobierno de la Ciudad para la creaci�n de sitios web.
Su prop�sito es que el trabajo in-house y de proveedores sea consistente est�tica y funcionalmente.

BAStrap est� basado en [Bootstrap v2.3.1](http://twitter.github.com/bootstrap)


## Compilar el CSS y JavaScript

BAStrap incluye un [makefile](Makefile) para compilar el framework. Antes de empezar instal� [las dependencias locales requeridas](package.json):

```
$ npm install
```

Una vez que est� instalado, vas a poder usar los comandos:

#### build - `make`
Corre el compilador recess para construir los archivos `/less` y compila los docs. Requiere recess y uglify-js.

#### watch - `make watch`
Este m�todo revisa los archivos Less y los compila autom�ticamente cuando los grab�s. Requiere Watchr.


## Autores originales

**Mark Otto**

+ [http://twitter.com/mdo](http://twitter.com/mdo)
+ [http://github.com/mdo](http://github.com/mdo)

**Jacob Thornton**

+ [http://twitter.com/fat](http://twitter.com/fat)
+ [http://github.com/fat](http://github.com/fat)


## Autores del GCBA

+ [Federico Abad](http://twitter.com/abad)
+ [Juli�n Rodriguez](http://twitter.com/julianrod)
+ [Te�filo Sibileau](http://twitter.com/drkloc)

## Copyright and license

Copyright 2012 Twitter, Inc.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this work except in compliance with the License.
You may obtain a copy of the License in the LICENSE file, or at:

  [http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
