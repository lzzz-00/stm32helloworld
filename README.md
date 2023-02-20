# stm32helloworld

# Reading Switch Inputs 

# Task
- Connect a 4-bit DIP switch to the STM32. (The 4-bit switch represent a value from 0000 to 1111)
- Write a program to read in the DIP switch value and display on terminal 
- Update the display only when the switch value change

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

# References
- https://microcontrollerslab.com/stm32-blue-pill-uart-interrupt-stm32cubeide/
