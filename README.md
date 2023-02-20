# stm32helloworld

# Reading Switch Inputs 

# Task
- Connect a 4-bit DIP switch to the STM32. (The 4-bit switch represent a value from 0000 to 1111)
- Write a program to read the DIP switch value and display on terminal together with Hello World
- Update the display only when the switch value change (example at below)

** Hello World
** 0000
** Hello World
** 1000

# Group 2
- Zhang Zhen
- Tian Linxue
- Lim Zhi

# Steps
1) Connect all the hardware through jumper on a breadboard (DIP switche is connected with pull up resistor)
2) Create a new project in STM32CudeIDE
3) Select the correct board (STM32F103C8)
4) Define DIP switch as input in Pinout & Configuration
5) Initialise USART in Pinout & configuration
6) Modify code inside the while loop (core/src/main.c)
7) Read the state of DIP switch using HAL_GPIO_ReadPin() 
8) If the DIP switch reading is not same as before, update the display
9) Configure the PuTTy (connection type -> serial, port -> 18, baudrate -> 115200)
10) The running result is displayed on PuTTy terminal as showned in the terminal.png attached above

# References
- https://microcontrollerslab.com/stm32-blue-pill-uart-interrupt-stm32cubeide/
