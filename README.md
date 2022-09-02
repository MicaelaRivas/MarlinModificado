# Marlin Modificado

- El propósito del código es ser cargado a la placa MKS Gen_L V2.1 para ser utilizada con los drivers TMC2209 V2.0 en la impresora de Melt Electrospinning del TFG "Diseño y fabricación de una máquina de Melt Electrospinning para Scaffolds" por Micaela Rivas
- Este código es el de Marlin (https://github.com/MarlinFirmware) con unas pequeñas modificaciones, éstas se señalan con el comentario "//modificado"

## Plataformas compatibles
- Arduino AVR: RAMPS, Melzi, RAMBo
- Adolescentes++ 2.0: Tablero de impresión
- Arduino Due: RAMPS-FD, RADDS, RAMPS4DUE
- ESP32: FYSETC E4, E4d@BOX, MRR
- LPC1768: MKS SBASE, Re-ARM, Selena Compact
- LPC1769: Smoothieboard, Azteeg X5 mini, TH3D EZBoard
- STM32F103: Malyan M200, GTM32 Pro, MKS Robin, BTT SKR Mini
- STM32F401: ARMADO, Rumba32, SKR Pro, Lerdge, FYSETC S6, Artillería Ruby
- STM32F7x6: El Borg, RemRam V1
- STM32G0B1RET6: BigTreeTech SKR mini E3 V3.0
- STM32H743xIT6: BigTreeTech SKR V3.0, SKR EZ V3.0, SKR SE BX V2.0/V3.0
- SAMD51P20A: Adafruit Grand Central M4
- Teensy 3,5		
- Teensy 3,6		
- Teensy 4.0	
- Teensy 4.1
- Linux native: Raspberry Pi


## Funcionamiento
Para que funcione el código hay que instalar Marlin (https://marlinfw.org) y modificar los archivos Configuration_adv.h y Configuration.h por los de este repositorio. Después se debe conectar el ordenador a la placa controladora y subir el programa, después de eso la placa ya estará lista para usarse. 
