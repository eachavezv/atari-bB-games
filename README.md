# Atari 2600 — batariBasic Games

Juegos para el Atari 2600 escritos en [batariBasic](http://www.bataribasic.com/), un lenguaje BASIC compilado para la consola.

## Juegos

| Archivo | Descripción |
|---------|-------------|
| `Falling_Alien.bas` | Juego de invasores: mueve tu nave con izquierda/derecha y dispara con el botón de fuego. Cada enemigo que no derrumbes duplica su velocidad. |
| `GAME1.bas` | Experimento con playfield y movimiento de sprite. |
| `GAME2.bas` | Experimento de juego #2. |
| `GAME3.bas` | Experimento de juego #3. |
| `GAME4.bas` | Experimento de juego #4. |
| `GAME5.bas` | Experimento de juego #5. |
| `GAME6.bas` | Experimento de juego #6. |
| `bordes_coordinados.bas` | Prueba de bordes y coordenadas. |
| `nave/nave.bas` | Prototipo de nave espacial. |

## Requisitos

- [batariBasic](http://www.bataribasic.com/) para compilar los archivos `.bas`
- Un emulador de Atari 2600 (como [Stella](https://stella-emu.github.io/)) para ejecutar los `.bin` compilados

## Compilar

```bash
bB.bat nombre_del_juego.bas
```

El binario resultante queda en la carpeta `bin/`.
