# CS-350-Emerging-Sys-Arch-Tech
# Project 1: Smart Thermostat Prototype

## Summary
In this project, our goal was to create a smart thermostat prototype using a TI board. The SysTec company, which specializes in analytics software for servers, wanted to enter the smart thermostat market. The project aimed to develop a low-level thermostat functionality prototype. It involved reading room temperature using the TMP006 temperature sensor (via I2C), indicating the output using an LED (LED on = heat on via GPIO), allowing users to adjust the set temperature using two buttons (via GPIO interrupt), and simulating data being sent to a server via UART. The long-term objective was to connect the thermostat to the cloud.

## What We Did Well
1. **Code Development**: We successfully developed code to handle various functionalities, including reading temperature, LED control, button presses, and UART communication.
2. **Peripheral Initialization**: We effectively initialized and utilized peripherals such as I2C, GPIO, and UART, demonstrating our ability to interface with hardware components.
3. **Task Scheduling**: We implemented a task scheduler that efficiently managed various actions, ensuring the system's smooth operation.

## Where We Could Improve
1. **Error Handling**: While we implemented error messages for some cases, there could be more comprehensive error handling to address potential issues and provide better diagnostics.
2. **Code Modularity**: Breaking down the code into more modular functions and commenting them thoroughly would enhance code readability and maintainability.
3. **Documentation**: Providing detailed documentation for the code, especially the task scheduler, would improve understanding and maintainability.

## Tools and Resources for Our Support Network
For future projects, we plan to leverage online forums, developer communities, and documentation related to embedded systems, TI boards, and specific hardware components like sensors and UART modules. Additionally, we will explore online courses and tutorials to enhance our skills further.

## Transferable Skills
Several skills from this project are transferable to other projects and coursework:
1. **Hardware Interface**: We gained experience in interfacing with hardware components like sensors, LEDs, and buttons, which is applicable to various embedded systems projects.
2. **Peripheral Initialization**: Knowledge of configuring and utilizing peripherals like I2C, UART, and GPIO is valuable for working with different microcontrollers and development boards.
3. **Task Scheduling**: Understanding and implementing task schedulers is crucial for multitasking applications, which are common in embedded systems.
4. **Coding Best Practices**: We applied coding best practices in terms of formatting and functional logic, which are essential for writing maintainable and readable code.

## Project Maintainability, Readability, and Adaptability
To ensure project maintainability, readability, and adaptability, we followed these practices:
- **Modularity**: We structured the code into functions to make it more modular, making it easier to update and maintain specific sections.
- **Comments**: We provided comments to explain the purpose and functionality of various code sections.
- **Coding Standards**: We adhered to coding standards to maintain consistency in naming conventions and formatting.
- **Documentation**: We included documentation for the task scheduler, detailing its algorithm, inputs, outputs, and expected results.
- **Error Handling**: While there's room for improvement, we included error messages to aid in debugging and maintenance.

Overall, this project allowed us to apply our skills in emerging systems architectures and technologies, and we're committed to continuous improvement in our embedded systems development journey.
