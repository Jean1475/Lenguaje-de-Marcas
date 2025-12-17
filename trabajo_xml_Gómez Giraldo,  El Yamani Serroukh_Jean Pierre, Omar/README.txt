En nuestro "Proyecto" usando XML y sus validadores DTD y XSD, hemos decidido usar el contexto de un sistema de reservas de un hotel. El XML está compuesto por:

- Una etiqueta raíz otorgada al elemento "Habitaciones".
- Cada habitación tiene un atributo id para diferenciarlas además de tener subelementos como "nombre_huesped", "edad" y "dni".

El DTD se va a encargar de verificar la estructura del XML. Tenemos la definición de elementos con el "ELEMENT" donde entre parentesís los subelementos que contienen. Con "ATTLIST" vamos a declarar los atributos de un elemento, indicando su nombre, tipo y si son obligatorios u opcionales.

Gracias a esto, el DTD asegura que nuestro XML siga la estructura correcta, sin errores de jerarquía ni de nombres de elementos o atributos.

/// Hecho por Jean Pierre ^