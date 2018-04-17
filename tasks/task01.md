# Tarea 01
## Descripción actividad
Jugadores y equipos. En el basketball, así como en otros deportes, los equipos se conforman por jugadores con diferentes caracteristicas. 

Usted debe implementar un modelo de datos utilizando Django 2 que permita modelar la situación descrita anteriormente. El modelo debe contener las siguientes características:

* El modelo Team debe tener los siguientes fields
    - Nombre del team
    - Descripción del team
    - Logo del team
    - Código de equipo

* El modelo player debe contener los siguientes fields
    - Nombre jugador
    - Apodo
    - Fecha de nacimiento
    - Edad
    - Rut
    - Email
    - Estatura
    - Peso
    - Fotografía
    - Posición de juego (opciones: Base, Escolta, Alero, Ala-pivot, Pivot)

Además de escribir el modelo en Django, debe configurar el administrador para que puedan ser administrados estos modelos. En el administrador debe configurar los siguientes elementos:

- Display de los registros: Para team debe mostrar el logo en miniatura del equipo (hint: lo puede reducir el tamaño con CSS), Para Player debe mostrar la foto del jugador
- Habilitar búsqueda para el apartado de players, donde permita buscar por nombre de jugador, apodo o RUT
- Habilitar filtro en apartado player, donde se pueda filtrar por team y fecha de nacimiento (este último debe ser horizontal)
- Habilitar búsqueda por nombre de team en apartado team

## Condiciones de entrega
* El proyecto debe estar versionado con GIT y gestionado a través de GITHUB
* Debe enviar el link del proyecto al email miguel [at] ewok [dot] cl 
* Asunto: DW2018-TAREA01
* Fecha de entrega: 17 Abril 2018

## Consideraciones
* Se evaluará el uso de GIT y GITHUB
* Se evaluará el uso de models en django
* Se evaluará el uso de admin y registro de apps

