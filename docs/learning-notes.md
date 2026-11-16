comence primero colocando etiquetas por que primeor lo quice hacer con html y css pero me di cuenta de que para esto seria demasiado extenso por recomendacion de un amigo y por que tenia algo en tailwind me ayudo e indico como darle forma a mis ideas luego le pedi ayuda a la i.a para colocar los parametros , debo segir practicando por que se me es algo complicado utilize esta pagina para colocarles los logos https://fontawesome.com/kits/c0ffb6cd5e/icons

## 16 de noviembre de 2026 - Prueba temporal con output.css

Al principio usé Tailwind con un enlace CDN porque era lo más sencillo para practicar.
Cuando publiqué el portafolio en GitHub Pages, vi que a veces se mostraba la foto,
pero los colores y las tarjetas no. El HTML sí cargaba, pero el script que crea
los estilos de Tailwind no siempre funcionaba.

Por eso dejé css/output.css dentro del repositorio. Este archivo tiene las reglas
que Tailwind genera a partir de las clases que escribí en el HTML. No las hice
una por una. Organicé el archivo para poder leerlo y entender dónde están
los colores, tamaños y espacios.

Comprendí que la semántica corresponde a las etiquetas HTML, como nav, main,
section y article. CSS solo define la apariencia. También corregí el botón
de correo para que sea un enlace a, porque span no abre direcciones.

Podría poner los estilos en un bloque style del index, pero serían muchas
líneas mezcladas con el contenido. Prefiero dejar un archivo CSS aparte
porque es más sencillo encontrar errores y mantener la página ordenada.


## 16 de noviembre de 2026 - Volví a Tailwind con CDN

Después de probar el archivo output.css, me di cuenta de que era una
solución más avanzada que lo que nos enseñaron. Mi trabajo consiste en
poner el enlace de Tailwind en el head y usar sus clases en HTML.

Por eso volví a https://cdn.tailwindcss.com y conservé la configuración
simple de mis tres colores. Quité el output.css del repositorio para
que el proyecto sea más fácil de entender y explicar. La prueba anterior
queda escrita arriba como parte de lo que intenté, pero ya no es la
solución que usa la página.

También entendí que, si el CDN no carga, los estilos no aparecen.
Todavía no sé cuál fue la causa exacta del error de la captura.
Si vuelve a ocurrir debo revisar el navegador con F12, abrir Network
y Console, comprobar si el script carga y probar la conexión.
No puedo decir que este cambio garantice que el CDN funcione siempre.
