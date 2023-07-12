1. Move to the directory you want to create the PetaLinux project in.
2. Create the project with ``` $ petalinux-create --type project --template zynq --name name ```.
3. Move into the project and configure using ``` $ petalinux-config --get-hw-description=design_wrapper.xsa ```, where design_wrapper.xsa is obtained from exporting a Vivado hardware description.
4. There is no need to change the default configuration settings, hit Exit.
5. ``` $ petalinux-build ```
6. The files we are interested in can be found in "images/linux".
7. Still from within the project folder, run ``` $ petalinux-package --boot --force --fsbl images/linux/zynq_fsbl.elf --fpga images/linux/system.bit --u-boot ```.
8. To deploy the PetaLinux project to the board, follow the instructions in PetaLinux_SD_Card_Partitioning.md.

Notes:
- PuTTY works as a terminal with its default settings, as long as the BAUD rate matches the board.
- There may be two recognized ports when the board is plugged in. In this case, use the latter port.
