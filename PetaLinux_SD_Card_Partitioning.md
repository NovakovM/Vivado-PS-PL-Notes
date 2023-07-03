1. Open disks
2. Go to the proper drive and create a new partition![image](https://github.com/NovakovM/Vivado-PS-PL-Notes/assets/84331501/4bd74cae-9038-43fa-9b04-dd0e342799f6)
3. This will be your boot partition, give it a minimum of 1GB for storage![image](https://github.com/NovakovM/Vivado-PS-PL-Notes/assets/84331501/050cbeaf-b61d-4875-b931-6499da256490)
4. Format it to be a FAT type![image](https://github.com/NovakovM/Vivado-PS-PL-Notes/assets/84331501/2a537345-3a5e-4ca6-91df-aeca8346131c)
5. Create another partition for the root. This one needs to be larger (minimum ~6GB), so you can allocate the rest of the drive space to it![image](https://github.com/NovakovM/Vivado-PS-PL-Notes/assets/84331501/18155e67-7aed-4b7d-abe8-07d5d9ca397f)
6. After building PetaLinux, the appropriate files can be brought to their partitions with the following commands![image](https://github.com/NovakovM/Vivado-PS-PL-Notes/assets/84331501/a561861e-24c7-4cbb-adf8-44a046102e43)
