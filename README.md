# Vivado-PS-PL-Notes
Instructions on PS-PL communication for FPGAs with on-board CPUs

General Vivado troubleshooting guide:
https://docs.xilinx.com/r/en-US/ug908-vivado-programming-debugging/Introduction

Installing board files for Vivado:
https://digilent.com/reference/programmable-logic/guides/installing-vivado-and-vitis#install_digilent_s_board_files

Notes:

- Bitstream file found in [project folder]/[project folder].runs/impl_1
- With an exported hardware design in newer versions of Vivado, a .sdk file will NOT be made and there will be a .xsa file instead. In Vitis IDE, create a new platform project using this .xsa file.
