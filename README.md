<img width="1400" height="700" alt="image" src="https://github.com/user-attachments/assets/303f4f0f-0308-4c0f-a48e-57bab5efcee2" />

Image: Original DanceDance Revolution Videogame, from which we drew inspiration.

# DanceDance Revolution Inspired Videogame implemented on a Zybo Z7 System on Chip (SoC) Development Board

Connections between processor and peripherals, as well as additional peripheral logic, is programmed in VHDL in Vivado Software. This is then implemented via a bitstream to the Zynq FPGA. An overview of block connections is described in the following block diagram:

<img width="1170" height="740" alt="hardware" src="https://github.com/user-attachments/assets/b989c715-3494-44b8-9af4-872af4c9be1d" />

The Software side runs inside the ARM Cortex-A9 Processor and is programmed with C. This is resposible for most of the game logic, screen animations and music. This is implemented through different functions and modules:

<img width="1258" height="759" alt="software" src="https://github.com/user-attachments/assets/9515e81d-10f2-4aa0-bfa8-08c642f61c3f" />


