


# Proyecto: Web de un restaurante con bootstrap, imágenes y vídeo.

#### Indice 

- [Descripción del proyecto :capital_abcd:](#Descripcion-del-proyecto)

- [Tecnologías empleadas :hammer:](###tecnologias-empleadas) 

- [Funcionamiento de la página :arrow_forward:](#Funcionamiento-de-la-página) 


- [Errores conocidos y prestaciones por desarrollar :no_entry:](#Errores-conocidos-y-prestaciones-por-desarrollar)  

#


# Descripción del proyecto

El proyecto consiste en la elaboración de una página web para un restaurante, inspirándonos en el ejemplo de la web de algún restaurante real. Habría de contener al menos una página principal, una carta, una galería, un apartado de reservas y además en su interior: imágenes, vídeo y elementos de bootstrap. Además habría de tratar de hacer el proyecto responsive para adaptarse a diferentes formatos de pantalla. 

### Tecnologías empleadas

HTML5 (utilizando un container-fluid y grid en lugar de display flex siempre que se ha podido para tener el resultado más responsive que el tiempo destinado al proyecto nos ha permitido alcanzar).
CSS3 (incluyendo técnicas como generar diferentes capas con z-index para poder poner un vídeo de fondo en index.html, about.html y restaurants.html).
Bootstrap:
-Carrusel (poner imagen del original de bootrap con sus 3 opciones y cómo lo hemos modificado para que además contenga 4).
-Modales para las imágenes de las galerías (mostrar el original de bootstrap y el nuestro).
-Modales dobles para la realización de las reservas (mostrar el original de bootstrap y el nuestro).
-Forms integrados en el modal doble para introducir los datos de reserva (mostrar el original de bootstrap y el nuestro).


### Funcionamiento de la página

  La página inicia en un index.html que nos permite a través de unos links centrales dirigirnos a restaurants.html o about.html.
  (foto de index.html)

  En about.html encontramos una declaración comercial del grupo restaurador y diferentes links que nos conducen o a index.html de nuevo o a las respectivas páginas de las diferentes propuestas de restauración.
  (Foto de about.html)

  En restaurants.html encontramos un link de regreso a index.html y un carrusel con links a las diferentes opciones de restauración ofrecidas.
  (Foto de restaurants.html)

  En las páginas principales de cada opción de restauración (abjasia.html, bangkok.html, caracas.html y toscana.html), encontramos: un link de regreso a index.html, un link que nos conduciría a su carta (carta.html), un link que nos conduciría a s galería de imágenes (galeria.html) y un modal para recoger reservas.
  (Foto de abjasia.html)

  En carta.html encontramos simplemente la información del respectivo menú, un link a index.html y otro a la página principal de la respectiva opción de restauración (ej.: abjasia.html).
  (Foto de carta.html)
  En galeria.html encontramos modales con las fotos asociadas a la respectiva opción de restauración y links para regresar a la página principal de la misma o a index.html.
  (Foto de galeria.html)

### Errores conocidos y prestaciones por desarrollar

No se ha podido disponer de el tiempo necesario para tornar about.html y restaurants.html totalmente responsives. Además en cuanto al sistema de recogida de reservas, simplemente se ha introducido un form que no recoge ningún dato ni gestiona ninguna reserva real. 
(Foto del form) 
