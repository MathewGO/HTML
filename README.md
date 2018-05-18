# HTML
Lo que fui aprendiendo en el curso


echo "# HTML" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/MathewGO/HTML.git
git push -u origin master

--Hacer que el padding no influya al momento de editar--
html {
	box-sizing: border-box;
}

*,*:before;*:after {
	box-sizing: inherit;
}

* {
	margin:0;
	padding:0;
}

-- --

--Hacer que el fondo quede fijo --
html {
	height: 100%;
}

body {
  height: 100%;
  background-repeat: no-repeat;
  background-attachment: fixed;
}

-- --

divs con bordes curvos

border-top-left-radius
border-radius: up right down left;
border-radius: 50%; --> Crea circulos;


imagen de background, se pueden insertar multiples imagenes, separadas por ',' manteniendo el orden al declarar formatos
background: url(../img/css3.png);
background-image:
background-repeat: no-repeat; repeat-y; repeat-x;
background-size: cover (la imagen toma el ancho y alto disponible de donde se esté aplicando);
background-position: center center; bottom right;


Colores:
1- Por nombre
2- Hexagesimal, #(hexa)

Cuando se hace selección con el mouse sobre un objeto, se puede hacer cambio de formato: ":hover"

Web Responsibe
@media only screen and (min-width: xxxpx) and (max: xxxpx) {

codigo CSS

}

Trabajar el formato en celulares:
en la etiqueta de html, agregar una meta con lo siguiente:
<meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">



