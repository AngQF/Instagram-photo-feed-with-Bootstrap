# ![4Geeks Logo](http://assets.breatheco.de/apis/img/images.php?blob&random&cat=icon&tags=4geeks,16) HTML Hello

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io#https://github.com/4GeeksAcademy/html-hello.git)

The most basic boilerplate for any 4Geeks Academy student using the [gitpod.io](gitpod.io) coding editor.

[![How to open html/css preview of my project in gitpod](https://github.com/4GeeksAcademy/Templates-Boilerplates/blob/master/assets/hello-html-intro.png?raw=true)](https://youtu.be/dfbDCMu_p-0)

## What to do next?

Create an `index.html` file with the [basic HTML structure](http://content.breatheco.de/lesson/what-is-html-learn-html#page-structure) and see it live by running a web-server using the following command:

```sh
$ pip3 install flask && python3 server.py
```

- You can create as many HTML files as you want
- You can also create CSS files and import them into your website using a `<link>` tag placed between the `<head></head>` tags, like this:

```html
<head>
  ...
  <link rel="stylesheet" type="text/css" href="styles.css">
  ...
</head>
```
EXPLICACIÓN:
Puse comentarios para separar el código y así guiarme mejor.

En index.html puse todo el contenido dentro de un div container-fluid para que se extendiera a lo ancho sin márgenes. Tanto en index.html como en cards.html todo el código de navbar y pagination es el mismo; solo que en cards.html lo separé dentro del header, porque el resto del contenido no ocupaba todo el ancho de la página como en el index.html.

Index.html: a las imágenes les tuve que poner una altura y ancho porque img-fluid solo ajusta el ancho y no encontré otra forma de ajustar el tamaño de la imagen como en el ejemplo.

Cards.html: el contenido del header es igual que en index.html, luego utilicé cards para cada imagen. Puse un id a cada card (aunque luego no lo use en css) para poder diferenciarlas mejor.