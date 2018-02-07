# Teclado latinoamericano (Linux Latam) para Mac

Este repositorio contiene un archivo de configuración y un­ícono para
configurar un teclado en Mac con la distribución latinoamericana tal como
funciona en Linux.

La principal razón para esto es que, a pesar de que hay varias alternativas,
ninguna contiene completamente el conjunto de caracteres especiales que aparecen
al combinar `AltGr + <key>` en Linux, o `option + <key>` en Mac. En Linux es
común usar caracteres como:

* `>` que se imprime con `AltGr + Shift + x`
* `<` que se imprime con `AltGr + Shift + z`
* `~` que se imprime con `AltGr + 4`

Para redireccionar la salida de un programa, representar la carpeta personal, o
dentro de vim para indentar un bloque de texto. 

## Instalación

Para instalar esta distribución de teclado desde la terminal de Mac sigue los
siguientes pasos:

1. Clona el repositorio con la siguiente instrucción:

   ```
   git clone https://github.com/geriom/Latam-mac.git 
   ```

1. Cambiar directorio a la carpeta que se acaba de crear:

   ```
   cd Latam-mac
   ```

1. Copia los archivos al directorio adecuado:

   ```
   cp Latam-linux.* ~/Library/Keyboard\ Layouts/
   ```

1. Reinicia tu computadora.

1. Añade el teclado a la lista de distribuciones disponible.

   * En la esquina superior derecha da click en el icono de la distribución
     de teclado que esta en uso. Luego da click en **Open Keyboard
     Preferences**. 

   * Da click en el signo de **+** en la esquina inferior izquierda del
     recuadro de configuracion que se abre.

   * Selecciona **Other** en la lista de idiomas de la izquierda. En el
     recuadro de la derecha aparece **Latam Linux**, seleccionalo y da click en
     **Add**.

A partir de este momento esa opción estará disponible para seleccionarla en la
barra de tareas o usando el atajo de teclado `control + Space`.
   
   
## Referencias adicionales

Este archivo de teclado está basado en [este](
https://github.com/neosergio/Latam-Keyboard). El ícono es el mismo.

Para más información sobre la creación de distribuciones de teclado para Mac
consulta [este
enlace](https://developer.apple.com/library/content/technotes/tn2056/_index.html#//apple_ref/doc/uid/DTS10003085-CH1-SUBSECTION13B).
