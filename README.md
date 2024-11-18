# Este es el README del proyecto final

## Explicación de la página

### Esta página es un ejemplo básico de una página para una panadería/repostería en donde se menciona un poco de la historia de por qué la panadería, un menú de los panes disponibles con imágenes y finalmente un formulario para realizar una orden de pan. A continuación se enlista cómo se fue realizando la página paso por paso

#### Paso 1: Se creó la carpeta para el proyecto final y se crearon los archivos index.html y README.md
#### Paso 2: Se creo el repositorio en github para el proyecto y se copió la url para hacer gitremote
#### Paso 3: Se inició git en la carpeta seleccionada y posteriormente se añadieron los archivos antes mencionados, se realizó el commit para iniciar el proyecto y finalmente se añadió la dirección del repositorio como git remote. A continuación se enlistan los comandos.
```
git init
git add index.html
git add README.md
git remote add origin <aquí va la url>
git commit -m "<aquí va el comentario>"
git push origin main
```
#### Paso 4: Se comenzó a hacer la página en index.html utilizando html:5 y completando con el tabulador, posteriormente se cambió el idioma de "en" a "es" dentro de la etiqueta html porque se la página está en español y en <title> se puso como título "Proyecto Final de DEV.F" y se empezó a trabajar en el <body>. Los metadatos de la etiqueta meta, no se modificaron ya que el set de caracteres a utilizar puede ser el de UTF-8
#### Paso 5: Se insertaron los encabezados de la página con las etiquetas h y el número correspondiente a su tamaño, se insertó una imagen que se subió previamente a imgur utilizando la etiqueta img y src para la url, y se reajustó el tamaño de la imagen para que no fuera mucho mas grande que los encabezados de la página web.
#### Paso 6: Los bloques de texto se insertaron usando la etiqueta <p>, Los íconos para ubereats y rappi se insertaron con la etiqueta <img> y se utilizó href para poner el enlace al que quermeos que nos redirijan. También se ajustó el tamaño de las imágenes para que no fueran más grandes que el texto.
#### Paso 7: Se añadió la lista de los productos utilizando la etiqueta ul y una imagen para cada uno de los productos en un tamaño menor al de la imagen de origen.
#### Paso 8: Se le pidio ayuda a chatgpt para el css, todo empezo porque queria justificar el texto, pero al final se le metieron como 15 pesitos de diseño donde se añadieron fondos, fuentes y estilos, se tuvo que modificar el html para que hubiesen clases, una clase para los iconos de delivery y otro para los iconos de redes sociales, y finalmente una clase para los fomularios de tipo radio y que de esa forma cada cosa matuviese un estilo independiente del otro, ya que de otra forma, no me era posible que solo lo de radio se modificase sin que lo demas quedara movido o chueco.