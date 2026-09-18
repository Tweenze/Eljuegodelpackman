# Actividad: Modificación y Optimización del Juego Pacman

Este repositorio contiene la implementación y modificación del juego clásico **Pacman**, desarrollado en Python utilizando la librería `freegames` y el módulo gráfico `turtle`. El código fuente base proviene de la documentación de [Free Python Games](http://www.grantjenks.com/docs/freegames/pacman.html) creada por Grant Jenks.

---

## 🛠️ Requisitos e Instalación

Para ejecutar este proyecto es necesario contar con Python 3 instalado y la librería `freegames`.

### Instalación de dependencias:
```bash
pip install freegames
🚀 Funcionalidades y Modificaciones Implementadas
El proyecto fue desarrollado en equipo integrando las siguientes mejoras sobre el código base:

Fantasmas Inteligentes: Se modificó la toma de decisiones de los fantasmas. En lugar de moverse de forma completamente aleatoria, evalúan los movimientos válidos y seleccionan la dirección que minimiza la distancia Manhattan hacia la posición actual de Pacman.

Rediseño del Tablero: Se actualizó la matriz tiles para ofrecer una nueva distribución de laberintos y pasillos.

Mayor Velocidad: Se incrementó la velocidad de desplazamiento de los fantasmas (aumentando su vector de movimiento por ciclo).

📂 Estructura del Repositorio
Plaintext
.
├── README.md      # Documentación general del proyecto
└── pacman.py      # Código fuente con las modificaciones integradas
🎮 Instrucciones de Ejecución
Para iniciar el videojuego, ejecuta en tu terminal dentro de la carpeta del proyecto:

Bash
python3 pacman.py
Controles:
⬆️ Flecha Arriba: Mover hacia arriba

⬇️ Flecha Abajo: Mover hacia abajo

⬅️ Flecha Izquierda: Mover hacia la izquierda

➡️ Flecha Derecha: Mover hacia la derecha

📋 Estándar de Documentación
El código fuente ha sido comentado y estructurado conforme a los estándares de documentación del Instituto, incluyendo la descripción de funciones, manejo de datos y lógica de colisiones.
