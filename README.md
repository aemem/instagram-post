
Este trabajo simula un post de instagram. Tiene un index.html y un main.css.

El html tiene un div con la clase "post" que tiene dentro un header, una foto y un footer. Este div tiene un ancho de 500px, margin: auto para centrarlo horizontalmente y un margin-top para centrarlo verticalmente. No tiene un padding para que la foto ocupe todo el ancho.

El header del post hay un div con la clase "header-left" que contiene el logo de HTML5 y en otro div el nombre de usuario y la localización. El logo es un icono de font-awesome. El usuario y la localización están en un div separado para poder colocarlos a la izquierda del logo usando float. A su vez el div "header-left" también tiene un float para que se quede a la izquerda del post.

A la derecha del header hay un a elipsis vertical que también es un logo de font-awesome y que también está colocado con float.

El header tiene un padding de 10px para separar los contenidos del borde.

Debajo del header está la foto a ancho completo con su texto alternativo correspondiente.

El footer está dividido en tres partes: los iconos de debajo de la foto, los likes, y la descripción de la foto. Cada una de estas partes es un div.

Los iconos son todos de font-awesome. Los tres iconos de la izquierda están agrupados en un div y tienen un float:left. El icono de bookmark tiene un float:right y un margint-top para separarlo de la foto.

Debajo está el div con los likes. Es un p con la parte de los usuarios que han dado like en negrita usando strong.

Por último está el div con la descripción de la foto que es un p con un lorem ipsum.

El footer también tiene un padding de 10px para separar los elementos de los bordes. 









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
