# Actividad 3
# Juego Pacman

> Este proyecto es una copia de Pacman en Python utilizando las librerías `turtle` y `freegames`. Permite al usuario controlar a Pacman dentro de un laberinto para comer puntos y esquivar fantasmas.
> Versión: 1
## Funcionalidades Base
- **Control:** Pacman se desplaza en la dirección elegida mediante las teclas de navegación (`Arriba`, `Abajo`, `Izquierda`, `Derecha`).
- **Sistema de Laberinto y Colisiones:** Representación del mapa mediante una cuadrícula de baldosas que define caminos transitables y paredes.
- **Mecánica de Juego:**
  - Recolección de puntos blancos distribuidos en el mapa.
  - Puntuación en tiempo real mostrada en pantalla.
  - Colisión y derrota al tocar a cualquiera de los fantasmas.
- **Fantasmas:** Cuatro fantasmas que se desplazan de forma aleatoria eligiendo una dirección válida cuando encuentran un obstáculo.

## Funcionalidades agregadas
- **Rediseño del mapa:** Se modificó la disposición de las paredes y pasillos en la matriz `tiles`,para una mayor variedad en el juego.

## Cambios en el código
- **Cambios en la matriz `tiles`:** Se modificó la lista de valores (0 para paredes, 1 para caminos) para generar el nuevo diseño del mapa.


## Requisitos e Instalación
1. Asegurarse de tener Python 3 instalado.
2. Instalar la librería requerida:
   ```bash
   pip install freegames
