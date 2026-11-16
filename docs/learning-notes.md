comence primero colocando etiquetas por que primeor lo quice hacer con html y css pero me di cuenta de que para esto seria demasiado extenso por recomendacion de un amigo y por que tenia algo en tailwind me ayudo e indico como darle forma a mis ideas luego le pedi ayuda a la i.a para colocar los parametros , debo segir practicando por que se me es algo complicado utilize esta pagina para colocarles los logos https://fontawesome.com/kits/c0ffb6cd5e/icons

## 16 de noviembre de 2026 - Por qué dejé output.css

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
