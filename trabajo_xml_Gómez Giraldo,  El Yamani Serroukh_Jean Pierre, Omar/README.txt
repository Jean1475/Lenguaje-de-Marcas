En nuestro "Proyecto" usando XML y sus validadores DTD y XSD, hemos decidido usar el contexto de un sistema de reservas de un hotel. El XML está compuesto por:

- Una etiqueta raíz otorgada al elemento "Habitaciones".
- Cada habitación tiene un atributo id para diferenciarlas además de tener subelementos como "nombre_huesped", "edad" y "dni".

El DTD se va a encargar de verificar la estructura del XML. Tenemos la definición de elementos con el "ELEMENT" donde entre parentesís los subelementos que contienen. Con "ATTLIST" vamos a declarar los atributos de un elemento, indicando su nombre, tipo y si son obligatorios u opcionales.

Gracias a esto, el DTD asegura que nuestro XML siga la estructura correcta, sin errores de jerarquía ni de nombres de elementos o atributos.

/// Hecho por Jean Pierre ^

Qué valida el XSD
El archivo esquema.xsd valida tanto la estructura como el tipo de los datos del XML.
Mediante el uso de tipos como xs:string, xs:integer y xs:date, se controla que los valores introducidos sean correctos.
Además, se aplican restricciones para asegurar que la edad esté dentro de un rango válido, que el DNI tenga un formato correcto y que el atributo id sea obligatorio y positivo.

Gracias a esto, el XSD permite una validación más completa y estricta del XML.

Dificultades encontradas
La principal dificultad durante el desarrollo del proyecto fue mantener la coherencia entre el XML, el DTD y el XSD, asegurando que todos validaran correctamente la misma estructura.
También fue necesario prestar atención al orden de los elementos y a la correcta definición de los tipos de datos.

//HECHO POR OMAR