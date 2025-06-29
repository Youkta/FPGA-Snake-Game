# Snake Game on FPGA using Verilog

Implementation of the classic Snake Game on an **FPGA (Field-Programmable Gate Array)**. This project recreates the game using **Verilog HDL**, with hardware-driven snake movement, fruit generation, and visual output via **VGA**.

## Features

* **Classic Snake Gameplay**  
  Real-time movement, fruit collection, and self-collision detection—all executed purely in hardware using synchronous logic.

* **Modular Verilog Design**  
  Game behavior is built using structural Verilog modules, with separate blocks for control, datapath, and rendering logic.

* **Fruit Generation with Pseudo-Random Logic**  
  A combinational pseudo-random generator ensures dynamic fruit placement on the grid.

* **VGA Display Output**  
  Visuals are output using an **800×600 VGA interface**, generated via a custom VGA timing module.

* **GPIO Pin Mapping**  
  FPGA input/output signals, including buttons and VGA connections, are assigned using a user-defined constraints (XDC) file.
