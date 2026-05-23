# Tetris Clásico en Python

Un juego de Tetris clásico implementado en Python con Pygame, que incluye mecánicas completas, sistema de puntuación, niveles de dificultad e interfaz gráfica.

## Características

✨ **Mecánicas Clásicas**
- Caída automática de piezas Tetris
- Rotación de piezas (90°)
- Movimiento horizontal
- Detección de colisiones

📊 **Sistema de Puntuación**
- Puntos por líneas completadas (100, 300, 500, 800)
- Bonus por nivel
- Tabla de puntuaciones persistente

🎮 **Niveles de Dificultad**
- 10 niveles (1-10)
- Velocidad incrementa con cada nivel
- Puntuación requerida para subir de nivel

🎨 **Interfaz Gráfica**
- Tablero visual en tiempo real
- Mostrador de siguiente pieza
- Puntuación en vivo
- Animación de líneas completadas

💾 **Persistencia**
- Guardar mejores puntuaciones
- Top 10 puntuaciones
- JSON para almacenamiento

## Requisitos

- Python 3.7+
- Pygame

## Instalación

```bash
git clone https://github.com/4kkt47gj27-max/tetris-game.git
cd tetris-game
pip install -r requirements.txt
```

## Uso

```bash
python main.py
```

## Controles

| Tecla | Acción |
|-------|--------|
| ⬅️ Izquierda | Mover pieza a la izquierda |
| ➡️ Derecha | Mover pieza a la derecha |
| ⬇️ Abajo | Acelerar caída |
| ⬆️ Arriba / W | Rotar pieza |
| ESPACIO | Pausar/Reanudar |
| ESC | Salir |

## Estructura del Proyecto

- `main.py` - Punto de entrada de la aplicación
- `game.py` - Lógica principal del juego
- `tetris.py` - Definición de piezas y tablero
- `ui.py` - Interfaz gráfica con Pygame
- `scores.py` - Gestión de puntuaciones
- `requirements.txt` - Dependencias del proyecto

## Mecánicas de Juego

### Puntuación
- 1 línea: 100 puntos
- 2 líneas: 300 puntos
- 3 líneas: 500 puntos
- 4 líneas (Tetris): 800 puntos
- Bonus: 50 puntos × nivel actual

### Niveles
- Comienza en nivel 1
- Cada 500 puntos = 1 nivel
- Máximo nivel 10
- Velocidad aumenta 10% por nivel

## Licencia

MIT License

## Autor

4kkt47gj27-max
