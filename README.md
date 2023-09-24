# STM32F4-Dicsovrey_Tutos
Blinking an LED with the STM32F4 Discovery board using STM32CubeMX and Keil uVision 5
Blinking an LED with the STM32F4 Discovery board using STM32CubeMX and Keil uVision 5 is a simple but fundamental project to get started with microcontroller development. In this project, you'll configure the microcontroller's GPIO (General-Purpose Input/Output) pins to control an LED, and you'll use a basic program to toggle the LED on and off at a specific rate. Here's a step-by-step description of the project:

*****Hardware Required:
*STM32F4 Discovery board
*USB cable for power and debugging
*A single LED (usually already present on the board)

*****Software Required:
*STM32CubeMX
*Keil uVision 5

*****Steps to create the project:
1-Install the necessary software: Make sure you have STM32CubeMX and Keil uVision 5 installed on your computer.

2-Open STM32CubeMX:
Create a new project.
Select your specific STM32F4 Discovery board (e.g., STM32F4 Discovery) from the list of available boards.

3-Configure the GPIO for the LED:
In the Pinout & Configuration tab, locate the pin connected to the onboard LED (usually labeled as LD1-LD2-LD3-LD4).
Set the mode of this pin to GPIO Output.
Make sure the initial state is LOW (LED off).
Save the pin configuration.

4-Generate the initialization code:
Click on the "Project", then "Generate Code" or similar option.
Choose Keil uVision 5 as your development environment.

5-Open the generated project in Keil uVision 5:
Import the project into Keil uVision 5.

6-Write the code:
In Keil, open the "main.c" file or create a new one.
Write a simple C program to toggle the LED.

7-Compile the code:
Build the project in Keil uVision 5. Make sure there are no compilation errors.

8-Load and run the code:
Connect your STM32F4 Discovery board to your computer via USB.
Flash the compiled code onto the microcontroller using the debugging tools in Keil uVision 5.
Run the code on the microcontroller.

9-Observe the LED:
You should see the onboard LED (LD1) blinking at a 1-second interval.

That's it! You've successfully created a project to blink an LED with the STM32F4 Discovery board using STM32CubeMX and Keil uVision 5. This project provides a solid foundation for more advanced STM32 development as you become familiar with configuring GPIO pins and writing code for the microcontroller.

Visite : https://www.youtube.com/@oussamatroudi/
Visite : https://github.com/OussamaTr
