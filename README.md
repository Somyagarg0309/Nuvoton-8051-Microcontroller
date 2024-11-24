# Nuvoton-8051-Microcontroller
# Project Overview
This project demonstrates two simple applications using the **Nuvoton 8051 Microcontroller**:

- **LED Blinking**: The LED blinks at a regular interval, showing basic control of GPIO pins.
- **LED Counter (0-9)**: An LED is used to represent numbers from 0 to 9, where each number is displayed by turning on a specific number of LEDs in sequence. This simulates a counter that progresses from 0 to 9.

# Project Objectives
- **LED Blinking**: This is the basic microcontroller operation where an LED connected to a GPIO pin blinks at a set interval (on/off).
- **LED Counter (0-9)**: We use a set of LEDs to create a counter that sequentially glows the LEDs to represent numbers from 0 to 9. The counter increments with each clock cycle and resets after reaching 9.

# Hardware Used
- **Nuvoton 8051 Microcontroller**: The main controller for the project.
- **LEDs**: A set of LEDs connected to the GPIO pins to show the blinking and counting functionality.
- **Resistors**: To limit current through the LEDs.
- **Breadboard and Jumper Wires**: For prototyping and connections.

# Software Requirements
- **Keil uVision IDE** (or any compatible 8051 IDE): For writing and compiling the code.
- **Nuvoton ISP ICP Utility**: For uploading the compiled HEX file to the Nuvoton 8051 microcontroller.
- **8051 Compiler**: Used within Keil or any other suitable 8051 IDE to compile the code into a HEX file.
- **Serial Terminal** (Optional): For monitoring the output if needed.

# Functionality Demonstrated
- **LED Blinking**: The LED blinks with a 1-second delay between on and off states. This demonstrates simple control over a GPIO pin using a microcontroller.
- **LED Counter (0-9)**: The LEDs light up sequentially from 0 to 9, simulating a simple counter. After reaching 9, the counter resets to 0 and repeats.

# How to Run the Project

### 1. Set up the hardware:
   - Connect the **Nuvoton 8051 microcontroller** to your breadboard.
   - Connect an LED to pin **P1.0** (for blinking).
   - For the LED counter, connect LEDs to **P2.5, P2.6, and P2.7** (for counting). Additional LEDs can be connected to other available pins (e.g., **P1.0 to P1.7**) as required, using appropriate current-limiting resistors.

### 2. Compile the code:
   - Open the project in **Keil uVision** or another compatible 8051 IDE.
   - Compile the code and generate the **HEX file** for the 8051 microcontroller.

### 3. Upload the code:
   - Use the **Nuvoton ISP (In-System Programming)** ICP (In-Circuit Programming) Utility to upload the compiled HEX file to the **Nuvoton 8051 microcontroller**.
   - Connect the **Nuvoton 8051 microcontroller** to your computer via the ISP programmer (such as **Nuvoton's USB-ISP tool**).

### 4. Power the circuit:
   - Provide power (typically 5V) to the **8051 microcontroller** and observe the LED behavior. The LED will blink at 1-second intervals, and the counter LEDs will display numbers from 0 to 9 in sequence.

# Conclusion
This project demonstrates basic **GPIO pin control** on the **Nuvoton 8051 Microcontroller**. By blinking an LED and implementing a simple LED counter (0-9), it showcases fundamental programming techniques for embedded systems, including delays, I/O control, and sequential logic.

