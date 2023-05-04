# STM32-With-LM35
Using STM32F103C8 read temperature value from LM35 and display it on LCD16x2.
# Project Overview
The software for this project consists of 5 files:
* main.c: this is the main file that read temperature from LM35 by ADC(Analog Digital Convert) and config LCD16x2.
* STM32F103C8_LM35.ioc: this is the file config for STM32 using CubeMX.
* CLCD.c and CLCD.h: library files for LCD16x2.
* STM32F103C8_LM35.pdsprj: this is the simulation file using Proteus Professional. I'm using Proteus version: 8.12.

In my main.c file, I have displayed the temperature value from LM35 to LCD by ADC and counted the running time.

Note: This is just a simple sample code file, you can refer to it and customize it for your own purposes.

To read temperature value from LM35 and display on LCD16x2 you have to create project using CubeMX and configure pins and open project with KeilC.
In the main.c file you need to write the functions as instructions. Besides, you need to add CLCD.C and CLCD.h libraries for LCD.
To do the simulation, you can create a new project using Proteus Professional or use the file I uploaded. Note, my Proteus file is only for version 8.12 and above.

Here are some pictures of the configuration steps for the STM342F103Cx, you can refer to it for more information.
![step1](https://user-images.githubusercontent.com/131508098/236118061-d94da201-a745-4d3a-980c-34b9af911f9c.jpg)
![serial_wire](https://user-images.githubusercontent.com/131508098/236118098-dab49e9d-6be8-4bdb-a864-5c4391981936.jpg)
![pins_configration](https://user-images.githubusercontent.com/131508098/236118119-e9468dd2-546f-406a-beab-55fc9f786bf4.jpg)
![adc](https://user-images.githubusercontent.com/131508098/236118121-f570615e-3ab8-4bc6-a8a9-1f9f82c85361.jpg)
![mdk_arm](https://user-images.githubusercontent.com/131508098/236118133-117532f8-657e-49c8-8c5f-66d973e71c66.jpg)
![proteus](https://user-images.githubusercontent.com/131508098/236118140-cbf7c19c-f57b-4c3f-804c-ce8983b9d9cb.jpg)
