# Vivado-PS-PL-Notes
Instructions on PS-PL communication for ZYNQ SoCs

General Vivado troubleshooting guide:
https://docs.xilinx.com/r/en-US/ug908-vivado-programming-debugging/Introduction

Installing board files for Vivado:
https://digilent.com/reference/programmable-logic/guides/installing-vivado-and-vitis#install_digilent_s_board_files

If your hardware target does not show up in Vivado, cabel drivers may not be installed properly:
https://support.xilinx.com/s/article/59128?language=en_US

Notes:
- Bitstream file found in [project folder]/[project folder].runs/impl_1
- With an exported hardware design in newer versions of Vivado, a .sdk file will NOT be made and there will be a .xsa file instead. In Vitis IDE, create a new project using this .xsa file and not from a repository
