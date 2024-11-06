# Apuntes-HTML

## Indice

[Comandos CMD Git](#comandos-cmd-git)

[Aprendizaje Teoría](#aprendizaje-teoria)

[Aprendizaje MarkDown](#aprendizaje-markdown)

<hr>

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

### Aprendizaje Teoria

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

### Aprendizaje MarkDown



[Volver al Indice](#indice)