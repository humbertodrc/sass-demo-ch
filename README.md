# sass-demo-ch

Un archivo con la extensión .css.map es un archivo de mapa de origen que se utiliza para hacer un seguimiento de la relación entre el código CSS compilado y el código Sass original. Los mapas de origen son útiles cuando se trabaja con código Sass compilado, ya que permiten ver y depurar el código Sass original en lugar del código CSS compilado.

Cuando se compila código Sass a CSS, se puede habilitar la creación de un archivo de mapa de origen utilizando la opción "--sourcemap" o "--sourcemap=true" al compilar. Una vez habilitado, Sass generará un archivo de mapa de origen junto con el archivo CSS compilado.

Para utilizar un archivo de mapa de origen, se debe vincular al archivo CSS compilado mediante la propiedad "sourceMappingURL" al final del archivo CSS. Por ejemplo
