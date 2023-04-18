Starting from after the welcome page when creating an application project:
![image](https://user-images.githubusercontent.com/84331501/231320743-128e945d-ca02-460d-879a-2553734518ee.png)

![image](https://user-images.githubusercontent.com/84331501/231320898-09415909-c0e7-4109-841b-d033e781ed07.png)
Select the XSA file which should be exported to the Vivado project location. Select generate boot components.

![image](https://user-images.githubusercontent.com/84331501/231321171-a9a09a1f-f31b-402d-95ec-0a2b6c47cb2f.png)
Name the application project. Select ps7_cortexa9_0.

![image](https://user-images.githubusercontent.com/84331501/231321483-ba001bf4-e14b-4366-a73f-c6f90d296d28.png)
Options get be left at default, though you may want to change the operating system to freertos.

![image](https://user-images.githubusercontent.com/84331501/231321633-58d933d7-38d9-4714-8887-0c29684e5f88.png)
Empty application C (or C++). Click finish.

Important directories:

  /wrapper/hw/drivers (files for custom ip blocks that contain register offsets)
  
  /wrapper/zynq_fsbl/zynq_fsbl_bsp/ps7_cortexa9_0/include/xparameters.h (file should always be called xparamaters.h and can be found in a few locations,    contains adress locations for ip blocks)
  
To run file (after building with the hammer icon):
![image](https://user-images.githubusercontent.com/84331501/232917242-c9f7cd00-0a4f-4c04-99c9-f08e55bf4901.png)
