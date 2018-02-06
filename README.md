# Teclado latinoamericano (Linux Latam) para Mac

Este repositorio contiene un archivo de configuraci√≥n y un√≠cono para
configurar un teclado en Mac con la distribuci√≥n latinoamericana tal como
funciona en Linux.

La principal raz√n para esto es que, a pesar de que hay varias alternativas,
ninguna contiene completamente el conjunto de carcteres especiales que aparecen
al combinar `AltGr + <key>` en Linux, o `option + <key>` en Mac. En linux es
com√n usar caracteres como:

* `>` que se imprime con `AltGr + Shift + x`
* `<` que se imprime con `AltGr + Shift + z`
* `~` que se imprime con `AltGr + 4`

Para redireccionar la salida de un programa, representar la carpeta personal, o
dentro de vim para identar un bloque de texto. 

## Instalaci√n

Para instalar esta distribuci√n de teclado desde la terminal de Mac sigue los
siguientes pasos:

1. Clona el repositorio con la siguiente instrucci√≥n:

   ```
   git clone https://github.com/geriom/Latam-mac.git 
   ```

1. Cabiar directorio a la carpeta que se acaba de crear:

   ```
   cd Latam-mac
   ```

1. Copia los archivos al directorio adecuado:

   ```
   cp Latam-linux.* ~/Library/Keyboard\ Layouts/
   ```

1. Reinicia tu computadora.

1. Anade el teclado a la lista de distribuciones disponible.

   * En la esquina superior dererecha da click en el icono de la distribucion
     de teclado que esta en uso. Luego da click en **Open Keyboard
     Preferences**. 

   * Da click en el signo de **+** en la esquina inferior izquierda del
     recuadro de configuracion que se abre.

   * Selecciona **Other** en la lista de idiomas de la izquierda. En el
     recuadro de la derecha aparece **Latam Linux**, seleccionalo y da click en
     **Add**.

A partir de este momento esa opci√n estar√° disponible para seleccionarla en la
barra de tareas o usando el atajo de teclado `control + Space`.
   
   
## Referencias adicionales

Este archivo de teclado est√ basado en [este]( https://github.com/neosergio/Latam-Keyboard). El √cono es el mismo.

Para m√s informaci√n sobre la creaci√n de distribuciones de teclado para Mac
consulta [este
enlace](https://developer.apple.com/library/content/technotes/tn2056/_index.html#//apple_ref/doc/uid/DTS10003085-CH1-SUBSECTION13B).
