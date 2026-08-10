# Entorno de Realidad Virtual Interactivo en Unity

Proyecto de realidad virtual desarrollado en Unity que combina diseño de entornos 3D, interacción con objetos y animación de personajes mediante un sistema XR.

## Descripción

El proyecto consiste en el desarrollo de un entorno virtual ambientado en un templo griego situado entre las ruinas de la Antigua Grecia.

El escenario está diseñado como un espacio tipo museo y se divide en diferentes zonas para guiar la experiencia del usuario:

- Zona exterior del templo.
- Sala de bienvenida.
- Zona de interacción y animación.

El entorno incorpora elementos arquitectónicos, estatuas, iluminación y materiales para crear una experiencia inmersiva en realidad virtual.

## Tecnologías

- Unity 2022.3.5f1
- OpenXR
- XR Interaction Toolkit
- C#
- Blender
- Animación 3D
- Modelado y assets 3D

## Interacción y animación

El proyecto incorpora diferentes elementos interactivos dentro del entorno virtual.

### Puerta interactiva

Se implementó un sistema de animación para una puerta mediante un Animator Controller y un sistema de triggers. El usuario puede activar la apertura mediante la interacción dentro del entorno de realidad virtual.

La lógica de interacción se controla mediante el script `ControlPuerta.cs`.

### Personaje animado

También se integró un personaje 3D con rig humanoide y diferentes animaciones.

El modelo fue procesado previamente en Blender y posteriormente integrado en Unity. Las animaciones se gestionan mediante un Animator Controller y se activan cuando el usuario se aproxima al personaje.

## Entorno 3D

El escenario representa un templo griego rodeado de ruinas de la Antigua Grecia e incluye diferentes elementos arquitectónicos y decorativos:

- Templo griego.
- Ruinas antiguas.
- Estatuas clásicas.
- Cuadros y elementos arquitectónicos.
- Iluminación y materiales 3D.

## Mi aportación

Participación en el desarrollo y configuración del entorno virtual, incluyendo el diseño de la escena, integración de elementos 3D, sistemas de interacción y configuración de animaciones dentro de Unity.

## Material del proyecto

El material completo del proyecto, incluyendo la memoria técnica, el vídeo de demostración y los archivos del proyecto, se encuentra disponible en el siguiente enlace:

' https://drive.google.com/file/d/1tf8v56wTePO7WJEwP58VPujjA_BOnj0u/view?usp=sharing '

## Documentación

La memoria técnica recoge información sobre el diseño del entorno, planificación visual, integración de assets, sistemas de interacción y animación.

## Proyecto académico

Proyecto desarrollado durante las prácticas de la asignatura de Realidad Virtual del Grado en Tecnología Digital y Multimedia de la Universitat Politècnica de València.
