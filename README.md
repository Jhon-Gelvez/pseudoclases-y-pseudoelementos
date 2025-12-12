# pseudoclases-y-pseudoelementos
Qué pseudoclases y pseudoelementos usó.
use ::after
para añadir un elemento adicional (texto)  y posicionarlo a la derecha respecto de otro  elemento en  este caso
h1::after {
    content: "👈 click";
    font-size: initial;
    position: absolute;
    width: 100px;

    top: 50%;
   
    transform: translate(-0%, -50%);
}

indicarle al usuario como interactuar con el TITULO

::before 
lo use para crear una caja  mas  grande  que su elemento y pocisionarla detras para añadirle una animacion 

:focus
lo use para que cuando el usuario le de un clik ocurra un estilo especifico dandole unteractividad a este elemento (img) y vida  a la pagina

:focus::before
al estar en estado de focus se cree o sea visible el ::before

:hover
al usuario pasar el raton por encima del parrafo este tendra un estilo diferente (se hara mas grande) dando un atractivo visual

li::marker
selecciona el contador de el elemento li y me permite darle estilos (cambiar su color)

Por qué los eligió.
me permiten hacer mas  interactiva  la pagina, mas atractiva y se sienta mas  viva, dandole una mejor experiencia al usuario

Qué retos enfrentó y cómo los resolvió.
ubicar  correcatamente los pseudoelementos ::after ::before ya que estos son relativos a la posicion de su elemento salen del flijo normar del documento y se debe usar 
top: 50%;
transform: translate(-0%, -50%);
para ubuicarlo respecto de su elemento

ubicar el cuadrado con la animacion detras de las imagenes las imagenes no tienen  ::after o ::before asi que le di un contenedor (div) y lo ouse para poder crear el cuadrado 
