InterfazAdquisicionNTSC
=======================

Código fuente del software para un STM32F4-DISCOVERY para la adquisición de una señal ITU-R BT.656 provista por un MAX9526 a partir de una cámara CCD con salida de video NTSC

## Instrucciones
**Instalación del Toolchain:**   
http://eliaselectronics.com/stm32f4-tutorials/setting-up-the-stm32f4-arm-development-toolchain      
**Debugging:**       
Instalar el debugger (gdb), guardar el nombre de la carpeta donde está su instalación y lo agregarlo al PATH. Conectarse a la tarjeta usando 'st-util'.     
Ejecutar 'arm-none-eabi-gdb main.elf' y luego usar 'tar ext: 4242'.
