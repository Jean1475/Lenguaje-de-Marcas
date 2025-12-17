En nuestro "Proyecto" usando XML y sus validadores DTD y XSD, hemos decidido usar el contexto de un sistema de reservas de un hotel. El XML está compuesto por:

- Una etiqueta raíz otorgada al elemento "Habitaciones".
- Un elemento "Habitación" a la que le hemos dado un id para diferenciarlas entre ellas.
- Elementos como "nombre_huesped", "edad" y "dni".

El DTD se va a encargar de verificar la estructura del XML. Tenemos la definición de elementos con el "ELEMENT" donde entre parentesís vamos a especificar los elementos que contiene. Con "ATTLIST" vamos a declarar los elementos que va a tener ese elemento primario, además de especificarle el nombre, tipo y estado del atributo.

Por último especificaremos otra vez con "ELEMENT" cada atributo que va a tener el elemento con su nombre y tipo.

/// Hecho por Jean Pierre ^