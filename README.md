# HTML

utf-8 Codificación universal 
  
     <meta  charset="utf-8">
Para que sea compatible con internet explorer

     <meta  http-equiv="X-UA-Compatible"  content="IE=edge">
Palabras clave para pocisionar la pagina

    <meta  name="keywords"  content=""> 
Descripcion breve de la pagina, no mas de 140/160 caracteres para que sea SEO frendly

     <meta  name="description"  content="">
Autor de la pagina

    <meta  name="author"  content="">
Copyright de la pagina web

    <meta  name="copyright"  content="">
Index = aparece en la busqueda de Google, noindex = no aparece en Google

    <meta  name="robots"  content="index">
Viewport = responsive en celulares

    <meta  name="viewport"  content="width=device-width, initial-scale=1">ode here

# CSS

 

 - asterisco(*) es un selector universal, pasa por encima de los demas selectores
-  "#" + nombre de id "#" selector de id, el id es unico y no se puede repetir
 - "." + nombre de las clase, selector de clases
 - [] + nombre del atributo. selector de atributos
- h2 p, para selecionar por descendiente
- !important, va por sobre todos los elementos
- :first-child
- em valor relativo, se puede heredar el valor o lo da por defecto el navegador
- vw (% de la pantalla a lo ancho, medida relativa); vh (% de la pantalla a lo largo, tambien medida relativa)
- display para cambiar el comportamiento dentro de la "caja"
- pseudo clases
    - :hover, al pasar el mouse por encima realiza una accion
    - :link, realizas cambios sobre cualquier  "a", o "link" que tiene un atributo href
    - :visited, modifica la apariencia de links ya visitados
    - :active, modifica la vista de los botones
    - :focus, se activa cuando el usuario hace clic, toca un elemento o lo selecciona con la tecla "Tab" del teclado
    - :lang, s utilizada para modificar elementos en función del idioma en el que se determina que están. ( p:lang(en) ) 
- object-fit, utilizado mayormente para imagenes
    - contein, se ajusta a las resoluciones del contenedor
    - cover, se ajusta al contenedor 
    - none, actua como la imagen original
    - scale-down, elige la resolucion mas chica
- object-position, determina el alineamiento del elemento dentro de la caja.
- cursor, cambia el cursor dentro de un contenedor especifico, se puede utilizar con pseudo clases
