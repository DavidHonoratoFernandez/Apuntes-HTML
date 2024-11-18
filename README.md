# Apuntes-HTML

## Indice

[Aprendizaje GitHub](#aprendizaje-github)

[Aprendizaje Teoría](#aprendizaje-teoria)

[Aprendizaje MarkDown](#aprendizaje-markdown)

<hr>

## Aprendizaje Github

Para empezar con GitHub, primero tenemos que conocer como podemos acceder a los repositorios, para ello, tenemos que dirigirnos a nuestro perfil, ubicado en la esquina superior derecha, en caso de no tener uno, lo creamos indicando nuestros datos:

![TextoAlternativo](./img/InicioGitHub.png "Inicio GitHub")

En el que se nos desplegará un panel lateral, donde indica las acciones que podemos hacer, seleccionaremos "Your repositories":

![TextoAlternativo](./img/MenuGitHub.png "Inicio GitHub")

A continuación veremos la sección de nuestros repositorios, pero como nosotros es crear uno, ignoraremos todos los repositorios e iremos al apartado "New", el cual se encuentra con un botón verde en la esquina superior derecha:

![TextoAlternativo](./img/CreacionRepoGitHub.png "Inicio GitHub")

Finalmente, estaremos en la sección de la creación del repositorio, en la que nos centraremos en tres zonas:

La primera, es el nombre del repositorio, que es básicamente el nombre que tendrá el repositorio donde estará todo lo que creemos después.

La segunda, es si queremos que el repositorio sea público o privado, en caso de ser público, está 100% accesible para cualquier usuario, la otra opción es privada, y, al contrario, solo nosotros decidiremos quien puede acceder.

Y por último, el archivo readme, que en este caso, es el archivo donde podremos ver el contenido en github sin necesidad de un archivo externo.

![TextoAlternativo](./img/ConfgRepoGitHub.png "Inicio GitHub")


### Comandos CMD Git

**Git init:** Para crear o reiniciar el repositorio en local.

**Git Branch:** Indica si el repositorio está en la rama “main”.

**Git Branch -M main:** Se utiliza en caso de que la rama no esté en la “main”.

**Git add README.md:** Sirve para solamente subir un archivo en específico al commit.

**Git add .:** Sirve para subir todos los archivos de la carpeta al commit.

**Git commit:** Sirve para preparar el commit.

**Git commit -m “mensaje":** Sirve para indicar un título/nombre a ese commit.

**Git push origin main:** Sirve para subir el commit. (Origin -> Origen) (Main-> Destino).

**Git clone "URL":** Clona el repositorio a local.

**Git remote add origin "link/url"** Crea un sitio origen en la url del repositorio de github.

**Git pull:** Coordina la versión de arriba (GitHub) con la local.

[Volver al Indice](#indice)

<hr>

## Aprendizaje Teoria

HTML (HyperText Markup Language) es el lenguaje de marcado estándar para crear paginas web. Lenguaje más importante de Internet dado que sin HTML no se vería nada en el navegador.

HTML. Define la estructura y el contenido (es decir, si hay una imagen, una lista de elemento, un enlace, un párrafo, un titular, etc…) de las paginas web mediante etiquetas, es muy adaptable, tiene una estructura lógica y es muy fácil de entender e interpretar. DESCRIBE EL CONTENIDO.

No se dedica a ver cómo se interactúa con el contenido (JavaScript, PHP, etc…) ni se preocupa por la presentación o estilizado del contenido, es decir, de como se ve el contenido (para eso tenemos CCS).

Los elementos HTML son los bloques de construcción de las páginas HTML.

Cada elemento HTML está delimitado por etiquetas, como ``<body>``, ``<head>``...

<br>

Las siglas de HTML corresponden con HyperTExt Markup Language, que tiene el siguiente significado:

Hypertext: cuyo significado es hipertexto, que no es mas que un texto que enlaza con otros contenidos, que pueden ser otro texto u otro archivo. Esto es la base del funcionamiento de la web tal y como la conocemos, que no es más que páginas y recursos interconectados.

Markup: Significa marca o etiqueta, ya que todas las páginas web están construidas en base a etiquetas, desde las primeras versiones hasta las últimas etiquetas de HTML5.

<br>

Elementos:

Es decir, HTML no es un lenguaje de programación.

Las partes principales del elemento son:

Etiqueta de apertura: Consisten en el nombre del elemento, encerrado por “< y >” paréntesis de apertura y cierre.

<br>

Los elementos pueden tener atributos:

Los atributos (class) contienen información adicional acerca del contenido, el cual se usa para darle un extra de estilo a una parte del texto en concreto, el cual será todos los elementos los cuales tienen la misma clase.
``<p class=”Nombre”>Texto ejemplo</p>``.

Una página HTML básica incluye una declaración DOCTYPE, un elemento html, y dentro, un head y un body.

**DOCTYPE:** Indica el tipo de documento.

``<html></html>``: Este elemento contiene todo el contenido de la página.

``<head></head>``: Es el contenedor de todo lo que queremos incluir en la pagina que no es visible.

En el head, se incluye:

``<meta />-- <meta>``: añade metainformación a la página.

Una descripción de la pagina que quieres que aparezca en resultados de búsquedas.
Palabras clave (**keywords**).

El título de la página: ``<title></title>``, como bien se indica, es el título de la página web.

El icono de la página (favicon): Podemos usar la etiqueta **_link_** y el atributo **_ref=”icon”_** para indicar el icono de la página.

El enlace con otros ficheros relacionados con el documento como hojas de estilo externa, código,…

Código CSS para dar estilo al contenido.

<br>

``<body></body>``: Es el contenedor de todo lo que queremos incluir en la página que SI es visible.

En el body, se incluye:

| Elemento | Definición |
|:----------|:-------------:|
| **Elemento de bloque**:  | Son grandes estructuras que contienen otros elementos de bloque, elementos de línea o texto. |
| **Elemento de línea**: | Son pequeñas estructuras que representan o describen pequeños trozos de texto o datos. |

<br>

En HTML, cuando necesitamos enlazar a otros archivos, ya sean documentos HTML, CSS, o imágenes, podemos usar dos tipos de rutas para especificar la ubicación de estos archivos:

| Ruta | Definición |
|:----------|:-------------:|
| **Ruta Absoluta**:  | Una ruta absoluta especifica la ubicación completa del archivo en la web, comenzando desde el dominio. Es útil cuando el archivo se encuentra en un servidor diferente o en una ubicación especifica en la web, por ejemplo, si queremos enlazar a una imagen que está en un servidor externo, usaremos: ``<img src=”https://www.example.com/images/logo.png” alt=”Logo de ejemplo”>`` |
| **Ruta Relativa**: | Una ruta relativa especifica la ubicación del archivo en relación con la ubicación del documento actual. Es útil para mantener una estructura de enlaces clara dentro de un mismo sitio web. Las rutas relativas pueden ser simples y facilitar el mantenimiento del sitio, especialmente cuando los archivos se trasladan o reorganizan. |

[Volver al Indice](#indice)

<hr>

## Aprendizaje MarkDown

Para empezar con Markdown, debemos saber como hacer encabezados, pero, antes de ello, tenemos que saber que hay diferentes niveles de encabezado, empezando por el primer al sexto nivel, para indicar dicho encabezado, tendremos que utilizar el "#", el nivel del encabezado depende del número de "#" que indiques, a continuación te dejo una explicación gráfica:

``# Primer nivel de encabezado``
<br>
``## Segundo nivel de encabezado``
<br>
``### Tercero nivel de encabezado``
<br>
``#### Cuarto nivel de encabezado``
<br>
``##### Quinto nivel de encabezado``
<br>
``###### Sexto nivel de encabezado``



### Formato de letras

Markdown ofrece una gran variedad de formatos, como por ejemplo, negrita, cursiva, o ambas.

Vamos paso a paso, a continuación verás como indicar todos los formatos:

**Negrita**: Para indicar la negrita tenemos que poner entre la palabra a editar dos "**" o "__", por ejemplo, ``**Palabra**`` o ``__Palabra__``, lo cual se vería así: **Palabra**.

**Cursiva**: Para indicar la cursiva tenemos que poner entre la palabra a editar un "_", por ejemplo, ``_Palabra_``, lo cual se vería así: _Palabra_.

**Ambas**: Para indicar ambas, tenemos que poner entre la palabra a editar dos "**" en los extremos y entre ambas un "_", por ejemplo, ``**_Palabra_**``, lo cual se vería así: **_Palabra_**.

### Listas

Para indicar la lista primero tenemos que saber que hay dos tipos, las ordenadas y las desordenadas, empezamos con las ordenadas.

#### Ordenadas

En las listas ordenadas, como dice el propio nombre, es una lista la cual se define por una serie de números, donde normalmente es usada para una página de pasos, para ello, tendremos que poner un "1., 2., 3., etc.", es importante saber, que si hay una sublista, es decir, una segunda lista en la lista principal, tendremos que tabular dicha parte, aquí un resultado gráfico:

1. Primer punto de la lista
    1. Primer elemento de la sublista 1
    2. Segundo elemento de la sublista 1
2. Segundo punto de la lista
    1. Primer elemento de la sublista 2
    2. Segundo elemento de la sublista 2


#### Desordenadas

En las listas desordenadas, como dice el propio nombre, es una lista la cual se define por una serie de puntos, guiones, básicamente, símbolos. Normalmente es usada para una página donde sean una serie de puntos, sin un orden en concreto, para ello, tendremos que poner un "*, -, +,", es importante saber, que si hay una sublista, es decir, una segunda lista en la lista principal, tendremos que tabular dicha parte, aquí un resultado gráfico:

* Primer punto de la lista
    * Primer elemento de la sublista 2
    * Segundo elemento de la sublista 2

* Segundo punto de la lista 
    - Segundo punto de la sublista 2
    + Tercer punto de la sublista 2


### Cómo mostar código

También podemos mostrar el código con markdown, ya sea para casos como este, de unos apuntes o de explicación, para mostrar el código específico, tendremos que poner acentos (3) entre el código, por ejemplo:

````
```
Código
```
````

Lo cual quedaría de esta forma:

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hola bro que tal picha</title>
</head>
<body>
    
</body>
</html>
```

### Como poner un link

Markdown ofrece la posibilidad de introducir links para dirigirnos a una página externa, para indicarlo, simplemente tenemos que indicar la URL, como añadido podemos escribir entre "[]" el texto que queramos que aparezca en pantalla, y luego después del enlace, entre comillas ("") poner un texto el cual aparecerá si ponemos el cursor encima, aquí ejemplo de como se aplicaría:

``[Página web inicio de sesión LaNet Jesuites Bellvitge](https://login.net.fje.edu/ "Página web de inicio de sesión del instituto")``

Así se vería el resultado:

[Página web inicio de sesión LaNet Jesuites Bellvitge](https://login.net.fje.edu/ "Página web de inicio de sesión del instituto")


### Como poner una img

A su vez también nos ofrece la posibilidad de instertar imágenes, en este caso ponemos la url de la imagen, y es importante empezar todo con una exclamación (!), los otros parámetros son idénticos al caso de la URL, y aquí un ejemplo:

``![TextoAlternativo](https://media.rpctv.com/p/41d66e950d9d22d3fb15a04a6ebd7e64/adjuntos/314/imagenes/018/718/0018718171/855x0/smart/raphinha-lamine-yamal.png "La mejor dupla de la actualidad")``

Aquí el resultado:

![TextoAlternativo](https://media.rpctv.com/p/41d66e950d9d22d3fb15a04a6ebd7e64/adjuntos/314/imagenes/018/718/0018718171/855x0/smart/raphinha-lamine-yamal.png "La mejor dupla de la actualidad")


### Como hacer una tabla

Para hacer una tabla, hay que saber un par de puntos, el primero de todos, es que si queremos tener una fila de encabezado, tenemos que indicar en la segunda fila, en lugar de texto, escribir guiones, el otro punto es que dependiendo de donde pongas los dos puntos(:) el texto se alineará en la izquierda, centro, o derecha, ahora lo vemos graficamente:

```
| Titulo 1 | Titulo 2 | Titulo 3 |
|:----------|:-------------:|---------------------------------:|
| SMX2 | Curso 2324 | 25 |
| **ASIX1** | Curso 2425 | 33 |
| DAW2 | Curso 2425  | 35 |
```

Como podemos apreciar, vemos que en la segunda fila, la indicamos con guiones para que la fila de arriba se interprete como encabezado, y luego en cada una de esas celdas de guiones, en caso de poner los dos puntos (:) en la izquierda, derecha, o ambas, orientamos el texto de una forma u otra, aqui vemos el resultado:

| Titulo 1 | Titulo 2 | Titulo 3 |
|:----------|:-------------:|---------------------------------:|
| SMX2 | Curso 2324 | 25 |
| **ASIX1** | Curso 2425 | 33 |
| DAW2 | Curso 2425  | 35 |

[Volver al Indice](#indice)