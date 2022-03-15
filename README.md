# SMART_KRONE
24 channel audio network recorder
The project is use 6 TI PCM1685 4-channel audio chips, read their I2S output streams. feed them into an FPGA for converting into 24 20msecond of audio PCM16 data. The 24 channel 20ms packets will be streamed to a WIZ610 Internet Offload Engine.
The WIZ chip and the FPGA will be controlled by an STM32 Cortex3 ARM MCU.
The products used to demonstrate this project works will the ude of the following evaluation boards
1 TI PCM1685-EVAL-Board
2 Lattice XP2-5 Brevia2_dev_board
WIZNET WIZ_6100_EVB, Containg ST STM32F103 ARM MCU and WIZ610 Network Offload Engine
