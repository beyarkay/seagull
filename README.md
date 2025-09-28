# Conway's Game of Life (entirely in hardware)

> NOTE:
>
> This is a KiCAD project, don't expect GitHub to play especially well with it.

|      Back Copper       |       Front Copper       |
| :--------------------: | :----------------------: |
| ![Back](imgs/back.png) | ![Front](imgs/front.png) |

This project implements Conway's game of life, entirely in hardware. Many
existing attempts to do this fail (IMO) in one of several ways. The features of
this project are:

- All logic is computed via logic gates, no microcontrollers are used
- Each cell in the game of life is an independent PCB, and cells can be
  disconnected/connected at will
