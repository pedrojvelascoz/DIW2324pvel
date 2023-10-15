El navegador elegido es Firefox
Versión 106.0.1 64-bits

Se cambia:
    - El background-color pasa de html al css
        - se actualiza de naranja a azul para comprobar el funcionamiento
    - color
        - se incluyen letras azules oscuro en todas las etiquetas "h".
        - se incluyen letras azules claro en la etiqueta "p"
            - se advierte un error en la tarea anterior. Una apertura de "p" en el último párrafo de "entorno"
    - texto
        - se justifican todos los textos de la etiqueta "p"
            - los textos alineados a center en planes no se aplican por el cambio
                - se les crea un id para especificar que sigan centrados
        - se añade un espaciamiento entre letras de 1px en la etiqueta "p"
        - se añade un margen al "body" para que la página tenga un margen de 2em
        - se añade un widht al 90% en el "body" para que el texto no llegue al final de la página

    - fuente
        - en las etiquetas "h", se establece fuente arial con peso bolder
        - en las etiquetas "p", fuente helvética, peso 200 y espacio entre líneas normal.

    - iconos 
        - se crea una etiqueta enlaceIndex en los iconos de la parte inferior de la página principal
        - sobre esta etiqueta, se realiza modificación
            el width se retira del html y se inluye dentro de la etiqueta

    - enlaces
        - se crea una etiqueta enlaceTxt para los botones de volver a la web principal
            - color de fondo azul y texto blanco arial centrado sin subrayado, con una caja relleno de 14x25.
            - cuando el usuario se situa encima, el cursor cambia a una mano
            - cuando el cursor está encima (hover) o se presiona el enlace (active), cambia el color de fondo y texto.
        - se crea una etiqueta enlaceMenu para los botones de menú de la web principal
            - características semejantes a la etiqueta anterior.
            - en este caso, cuando un botón ha sido vistado cambia el color de fonto y texto.

    - listas
        - a la liste existente en el index:
            - se le quitan los puntos para que no se vea como una lista
            - se le pone inline, queda mejor alineado

    - tablas
        -vamos a modificar la tabla "planes". Lo hacemos para el elemento "table" en general
            - se colapsa el borde y se le da formato

    - formularios
        - se hace un focus en el text-area cuando se escribe
        - se modifican los inputs de tipo texto
        - se podrían modificar los botones igual que se ha hecho con los enlaces o iconos

    - propiedades de posicionamiento
        - sobre el index, se crean dos divs: el meno web y la imagen con los iconos
        - se posicionan correctamente para que cambie la manera en que se ven

    - modelo de caja
        - se ha usado, en los elementos anteriores:
            - padding
            - margin
            - widht
            - height 