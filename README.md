# Prueba de reclutamiento: Web game programmer

Gracias por tomarte el tiempo de realizar esta prueba de codificación para la vacante "Web Game Programmer".

----

## Prerequisitos / Environment


La prueba técnica para Web Game Programmer debe ser desarrollada con la siguiente versión de Phaser:

  **Phaser:** `3.55.2`

## Tareas

Te hemos proporcionado un escenario creado en el software "Tiled" map editor, Este mapa (map.json) en conjunto con el tileset (baseTileset.png) contiene la información necesaria para poder cargar y visualizar el escenario en tu proyecto de phaser.

Además, el mapa contiene información que podría ser funcional para algunas de las tareas que se solicitarán a lo largo de esta prueba.

<img src="https://github.com/jesgonzalezGC/Prueba-Web-Game-Programmer/blob/main/assets/MapReference.PNG" width="500" />

- Cargar el escenario de Tiled en phaser.
  - Se deberá montar el mapa proporcionado en este repositorio en una escena de phaser.
- Añadir colisiones del mundo (información en el map.json).
- Personaje con animaciones.
  - Se deberá integrar el personaje que se encuentra en la carpeta assets (player.PNG), siendo la mecánica principal caminar con las teclas WASD además que debe reproducir su animación al caminar.
- Añadir UI a el juego (libre).
  - Eres libre de realizar esta interfaz a tu criterio
- Interación y eventos
  - En las 2 casas que se encuentran en el escenario el usuario puede interactuar con algún objeto de tu elección y así poder "entrar" a <b>un</b> minijuego (Estos minijuegos deben estar en otra escena).
  - El minijuego puede ser cualquiera pero te damos algunos ejemplos: 
    - Rompe bloques estilo "Arkanoid"
    - Snake
    - Buscaminas
    - Pac-man
    - Avoid and pickup falling objects

## Extras
- Luces y partículas
  - Agregar algunas luces y partículas ya sea en el escenario principal o los minijuegos.
- Pausar juego
- Spawn point marcado desde Tiled
- Agregar algún shader 

## Submission Guidelines
* El proyecto debe ser exportado en formato zip, el cual debe llamarse {yourname}.zip, y dentro debe contener otro directorio llamado web-game-programmer-test con tu solución lista.
* Dentro de tu solución debes añadir un archivo con las instrucciones para poder ejecutar tu proyecto con normalidad.

