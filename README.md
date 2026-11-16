# My Portfolio
Hi! My name is Ramael Gonzalez. I am learning software development at Riwi.

I made this portfolio to introduce myself, show my skills, and share my projects. I wanted a simple website with a dark background and green colors.

## How I made it

I started with HTML to organize my page. I used `header`, `nav`, `main`, `section`, `article`, and `footer` to keep my code clear.

I used Tailwind CSS with a CDN link, just like I learned in class. I add classes in my HTML for colors, spaces, borders, and layouts. My custom colors are `principal`, `verde`, and `acento`.

I also created three colors for my website:

- `principal`: dark green
- `verde`: green
- `acento`: bright green

I used Flexbox for the menu and the introduction. I used Grid for my skills and project cards.

I also used responsive classes like `md:flex-row` and `md:grid-cols-3` to change the layout on different screen sizes.

I used Tailwind CSS for the full design, including the small green label under my introduction.

## What is on my website?

- Home: my name, photo, and introduction.
- About me: my interests and goals.
- Skills: HTML, CSS, JavaScript, and Tailwind.
- Projects: Rueda Libre, Algoritmia, and future projects.
- Contact: my GitHub profile.

## What I learned

I learned how to use Tailwind CSS without writing a lot of CSS code.

I practiced HTML structure, Flexbox, Grid, colors, spacing, and responsive design.

The most difficult part for me was choosing the correct Tailwind classes and organizing the page for mobile and desktop.

I still need more practice, but this project helped me understand how to build a website.

## How to open my project

1. Download the project files.
2. Open the HTML file in Visual Studio Code.
3. Open the website with Live Server.
4. Keep an internet connection because Tailwind CSS loads from a CDN link.

The profile image must be in the correct folder. The contact button opens an email message with my address as the recipient.

## My GitHub

https://github.com/Ramael-L

This is my learning project. I want to improve it as I learn more about programming.

## Live website

https://ramael-l.github.io/Portafolio/
 
## Why I returned to Tailwind CDN

When I opened my published website, some Tailwind styles did not appear. We tried saving the generated CSS in a separate `output.css` file. It worked as another way to load styles, but it was more complicated than what I had learned.

I decided to use the CDN link again and keep Tailwind classes in my HTML. I do not need a compiled CSS file for this class exercise. If styles do not load again, I should check my internet connection and the browser's Network and Console panels. The original problem was not confirmed to have one specific cause.

## Actualización del enlace de Tailwind (16/11/2026)

Al abrir el portafolio en GitHub Pages, vi que la imagen aparecía, pero los colores y las tarjetas no. No pude confirmar la causa exacta desde el navegador. Primero probamos un archivo output.css, pero lo quitamos porque en clase usamos Tailwind directamente desde un enlace CDN.

Después cambiamos el enlace de Tailwind v3 por el CDN oficial de Tailwind v4, alojado en jsDelivr. Sigo poniendo las clases directamente en el HTML. Los tres colores de mi portafolio se definen en un bloque pequeño de @theme dentro del head. No tengo que instalar ni compilar archivos.

El navegador necesita internet para descargar Tailwind. Si vuelve a fallar, debo revisar F12 > Network y Console, además de comprobar el zoom de Chrome con Ctrl + 0. No considero resuelto el problema hasta comprobar la página desde mi navegador.


## Fixing my colors (16 November 2026)

When I opened my published portfolio, the background was white, the links were blue, and some text was hard to see. The HTML loaded, but my colors were different. I found that Bootstrap CSS and Tailwind v4 were both styling the same page. Bootstrap styles could override Tailwind colors.

I removed the full Bootstrap stylesheet because the portfolio only used it for one small badge. I replaced that badge with Tailwind classes. I kept my original colors: dark green `#0b1713`, green `#1E7A4F`, and bright green `#36D98A`.

I still use Tailwind directly from the CDN, with no generated `output.css`. I need to check the complete published page in my browser, including the links and responsive view.
