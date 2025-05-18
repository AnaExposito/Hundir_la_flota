# Hundir la Flota (Nombre de tu Repositorio)

¡Bienvenido al juego de Hundir la Flota! Este es una implementación en Python del clásico juego de mesa en el que dos jugadores 
intentan hundir la flota enemiga antes de que la suya sea destruida.

## Cómo jugar

1. **Requisitos:**
     * Phtyon
     * Liberias: numpy - time - random

2. **Estructura:**
    * Main: Juego
    * Utils: Funciones
    * Variables: Lista

3.  **Configuración inicial:**
    * El juego comenzará con un mensaje de bienvenida.
    * Se mostrarán los tableros iniciales (vacíos).
    * Tus barcos se colocarán automáticamente en el tablero.
    * Los barcos del rival también se colocarán automáticamente (ocultos).

4.  **Turnos:**
    * El juego se desarrolla por turnos, comenzará el rival.
    * En tu turno, se te pedirá que introduzcas las coordenadas (fila y columna) donde deseas disparar al tablero del rival.
    * El resultado de tu disparo (impacto o agua) se mostrará en el tablero de disparos del rival.
    * Luego, será el turno del rival para disparar a tu tablero.
    * El disparo del rival y el resultado también se mostrarán.

5.  **Objetivo:**
    * El objetivo es hundir todos los barcos del rival antes de que el rival hunda todos tus barcos.
    * Un barco se considera hundido cuando todas sus casillas han sido impactadas.

6.  **Fin del juego:**
    * El juego termina cuando todos los barcos de un jugador han sido hundidos.
    * Se mostrará un mensaje indicando al ganador y los tableros finales de ambos jugadores.

## Características

* Implementación del juego clásico de Hundir la Flota.
* Tableros de 10x10.
* Colocación automática de barcos para ambos jugadores.
* Interfaz de texto interactiva para la entrada del jugador.
* Muestra el tablero de disparos del rival y el tablero de barcos del jugador en cada turno.
* Mensajes sobre impactos, fallos y el fin del juego.
