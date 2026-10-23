# Hundir la Flota en Python ⚓️

Proyecto en Python inspirado en el clásico juego de **Hundir la Flota** (*Battleship*).

Cada jugador comienza con 6 barcos distribuidos aleatoriamente por el tablero que simula la posición en el mar mediante unidades, " ".
Se asume que las porciones de mar en las que se encuentra cada flota son disjuntas.
El juego consiste en disparar al tablero del adversario con el fin de destruir su flota.
Para este propósito los jugadores se turnan para ejecutar un único disparo que puede:
- destruir una unidad de eslora (la unidad de eslora pasa a ser "X" en su posición en el tablero)
- volver a disparar a una unidad de eslora ya destruida (la unidad de eslora sigue simbolizándose por "X")
- disparar a una unidad de agua (la unidad de agua pasa a ser "-")
- disparar fuera del tablero (se pide otro intento)


## Características principales

- 🎯 Juego por turnos: jugador vs. máquina.
- 📋 2 tableros para barcos y 2 para disparos.
- 💥 Impactos, hundimientos y detección de ganador.

## Estructura del proyecto
```
Hundir la flota/
├── main.py         # lógica del juego
├── utils.py        # funciones del juego
└── README.md
```
## Requisitos

- Python 3.x
- Numpy (`pip install numpy`)

## Cómo ejecutar

```bash
python main.py
```