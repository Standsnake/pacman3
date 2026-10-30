# Actividad 3
# Juego Pacman

> Este proyecto es una copia de Pacman en Python utilizando las librerías `turtle` y `freegames`. Permite al usuario controlar a Pacman dentro de un laberinto para comer puntos y esquivar fantasmas.
> Versión: 2
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
- **Aumento de velocidad:** Se subió la velocidad de movimiento de todo el juego (fantasmas y pacman) para tener un juego más fluido..
## Cambios en el código
- **Cambios en la matriz `tiles`:** Se modificó la lista de valores (0 para paredes, 1 para caminos) para generar el nuevo diseño del mapa.
- **Aumento de velocidad de los fantasmas:** En la lista `ghosts` y dentro de `options` de la función `move()`, se incrementaron los pasos del movimiento de 5 a 10 unidades.
- **Aumento de velocidad de pacman:** Se modificó la dirección inicial `aim` a `vector(10, 0)` y se cambió (`onkey`) a pasos `10` y `-10` unidades para mantener el equilibrio con los fantasmas.

## Requisitos e Instalación
1. Asegurarse de tener Python 3 instalado.
2. Instalar la librería requerida:
   ```bash
   pip install freegames
