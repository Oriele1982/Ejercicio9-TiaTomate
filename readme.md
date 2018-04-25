# Maquetación - Front End G7 2018

## Pre-maquetado de página Tía Tomate:

La empresa productora de tomates orgánicos llamada **Tía Tomate** pide crear una maqueta de la página "acerca de".

En ella desean mostrar a sus clientes una pequeña reseña sobre su historia, la procedencia de sus productos y mostrar a las personas que trabajan cosechando estas verduras.

Según sus requerimientos la página debe:

- Ser responsiva
- Mostrar la pasión que sienten por sus tomates
- Dar enfásis a la compra de sus productos
- Mostrar el logo de la empresa.

### Desarrollo: 

Para realizar la maquetación de la página Tía Tomate, tenemos como referente el mockup realizado por el diseñador anterior el cual nos adjunta una guía de estilos para poder realizar dicha página.

# PASO 1 - SKETCH:

1.- Antes de todo, debemos comenzar con el proceso de PRE-MAQUETADO, el cual está realizado en sketches realizados en papel, representativos de la página. Estos muestran 2 versiones de visualización para : ESCRITORIO y DISPOSITIVOS MÓVILES. (Archivos de imágenes de los sketch adjuntos en carpeta img.)

2.- En los sketches se identifican el número de secciones (bloques) que hay en la estructura de la página HTML (en este caso 4 + navbar y footer), para luego identificarlas con un nombre-clase correspondiente para darle estilos en CSS.

	 **SECCIONES**
		 -Navbar
		1-Header
		2-Products
		3-Blog
		4-Contact
		 -Footer



3.- Dentro de las secciones se localizan los elementos que las componen segun lo visualizado en el mockup (títulos, subtítulos, párrafos, imágenes, botones, íconos).

# PASO 2 - CREACIÓN DIRECTORIO Y DEPENDENCIAS PÁGINA TIA TOMATE:

1.- Para poder realizar la página debemos comenzar con la creación de nuestro DIRECTORIO DE PÁGINA WEB el cual consta de una carpeta con el nombre del proyecto (Actividad9-Tiatomate) en cuyo interior sigue la subcarpeta assets y luego el resto del contenido. El esquema podría visualizarse de la siguiente manera:

  Assets
  	|
  	|--css
  	|   |- style.css
  	|
  	|--fonts
  	|   |--______.tff
  	|
  	|--img (imágenes)
  	|   |-- _____.jpg
  	|   |-- _____.jpeg
  	|   |-- _____.png
  	|
  	|--js
        |--script.js
  
  index.html
  readme.md

  2.- Una vez realizado el directorio, procedemos a construir nuestro HTML y no debemos olvidar utilizar las DEPENDENCIAS DE LA WEB para que nuestra página quede y funcione mejor.

  	**DEPENDENCIAS**
  	- CDN BOOTSTRAP   -- RESPONSIVE / ESTILOS / GRILLA
  	- CDN JQUERY      -- LIBRERÍA JAVASCRIPT
  	- CDN FONT AWESOME -- UTILIZACIÓN DE ÍCONOS
  	- CDN GOOGLE FONTS  -- UTILIZACIÓN DE FUENTES DE GOOGLE

  	**No olvidar también enlazar los archivos locales css y js**

# PASO 3 - CREACIÓN ESTRUCTURA PÁGINA TIA TOMATE :

 1.- Para la creación de la página, debemos considerar el sketch realizado para identificar las secciones que se encuentran dentro de esta estructura (mencionadas anteriormente).

 2.- Viendo la disposición de los elementos en el sketch podemos considerar trabajar con un layout de 2 columnas para la versión de ESCRITORIO  y un layout de 1 columna para la versión mobile.

 3.- Luego comenzamos con la construcción misma de la página, y por medio de la METODOLOGÍA BEM, le daremos las clases respectivas a los elementos para poder darle estilos en css.


# PASO 4 - CREACIÓN ESTILOS PÁGINA TIA TOMATE :







