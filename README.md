# Entorno de Realidad Virtual Interactivo en Unity

Proyecto de realidad virtual desarrollado en Unity que combina diseño de entornos 3D, interacción con objetos, físicas y animación de personajes mediante un sistema XR.

## Descripción

El proyecto consiste en un entorno virtual ambientado en un templo griego situado entre las ruinas de la Antigua Grecia.

El escenario está diseñado como un espacio tipo museo y se divide en diferentes zonas para guiar la experiencia del usuario:

- Zona exterior del templo.
- Sala de bienvenida.
- Zona de interacción y animación.

El entorno utiliza iluminación, materiales y elementos arquitectónicos 3D para crear una experiencia inmersiva.
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

Se implementó una puerta animada mediante un sistema de Animator y triggers. El usuario puede activar la apertura mediante la interacción con el entorno VR.

La animación utiliza un controlador `Animator` y el script `ControlPuerta.cs` para detectar las interacciones del sistema XR. :contentReference[oaicite:3]{index=3}

### Personaje animado

También se integró un personaje 3D con rig humanoide y animaciones.

El modelo fue procesado previamente en Blender y posteriormente integrado en Unity. Las animaciones fueron configuradas mediante un Animator Controller y se activan cuando el usuario se aproxima al personaje. :contentReference[oaicite:4]{index=4}

## Entorno 3D

El escenario combina diferentes elementos arquitectónicos y decorativos, incluyendo:

- Templo griego.
- Ruinas antiguas.
- Estatuas clásicas.
- Cuadros y elementos arquitectónicos.
- Iluminación y materiales PBR.

Los recursos 3D utilizados proceden de diferentes fuentes y fueron integrados y procesados para su utilización dentro del entorno de Unity.

## Mi aportación

Participación en el desarrollo y configuración del entorno virtual, incluyendo el diseño de la escena, integración de elementos 3D, sistemas de interacción y configuración de animaciones dentro de Unity.

## Documentación

Se incluye la memoria técnica del proyecto con información sobre el diseño del entorno, planificación visual, sistemas de animación e implementación técnica.

## Demostración

Se incluye un vídeo mostrando el funcionamiento del entorno virtual y sus principales elementos interactivos.

## Proyecto académico

Proyecto desarrollado durante las prácticas de la asignatura de Realidad Virtual del Grado en Tecnología Digital y Multimedia de la Universitat Politècnica de València.
