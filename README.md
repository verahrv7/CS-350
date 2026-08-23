# CS 350 Smart Thermostat Project

## Project Summary

For this project, I created a smart thermostat prototype using a Raspberry Pi 4B. The goal was to create a system that could read the room temperature, allow the user to change the temperature set point, and switch between Off, Heat, and Cool modes. I used an AHT20 temperature sensor, an LCD display, buttons, and red and blue LEDs. I also used UART to simulate sending thermostat data to a server. Another part of the project was comparing different hardware architectures and deciding which one would be a good choice for a future version that connects to the cloud.

## What Did I Do Particularly Well?

I think I did well combining the hardware and software parts of the project. I was able to get the temperature sensor, LCD, buttons, LEDs, and state machine working together. I also learned a lot from troubleshooting the project when something did not work the way I expected. Instead of changing everything at once, I learned to test different parts of the system and find where the problem was coming from.

## Where Could I Improve?

One area I could improve is planning my testing and demonstrations more carefully. During my final project demonstration, I showed most of the thermostat states, but I did not demonstrate every possible LED condition. In the future, I would make a checklist of all the requirements before testing or recording a demonstration. This would help me make sure that I do not miss any important functionality.

## Tools and Resources

Throughout this course, I learned that documentation and other technical resources are very important when working with unfamiliar hardware or software. I used course materials, Python documentation, hardware documentation, examples, and troubleshooting information to help solve problems. I will continue using these types of resources in future projects instead of expecting to know every answer immediately.

## Transferable Skills

The biggest skills I can take from this project are troubleshooting, working with hardware and software together, and breaking larger problems into smaller steps. I also gained more experience with Python, GPIO, I2C, UART, state machines, and embedded systems. These skills will be useful in future computer science courses and in other projects involving hardware, IoT devices, or software that communicates with physical components.

## Maintainability, Readability, and Adaptability

I tried to keep my code organized by separating different functions of the thermostat into methods and using a state machine for the Off, Heat, and Cool modes. I also used comments and meaningful names to make the code easier to understand. Keeping the different parts of the program separated makes it easier to troubleshoot and also makes it possible to change or add functionality later without rewriting the entire program.
