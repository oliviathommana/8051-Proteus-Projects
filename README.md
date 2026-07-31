me · MD
8051 Proteus Projects

A collection of 8051 microcontroller (AT89C51/AT89S52) simulation projects built and tested in Proteus Design Suite. Each project includes the Proteus schematic (.pdsprj), Keil C source code, and a compiled hex file for simulation.

📋 Overview

This repository contains beginner-to-intermediate level 8051 projects demonstrating core embedded systems concepts — GPIO control, interfacing with displays, timers/interrupts, serial communication, and analog-to-digital conversion — all simulated in Proteus before hardware deployment.

🛠️ Tools Used
Proteus Design Suite – circuit simulation
Keil µVision (C51) – firmware development and compilation
8051 family microcontroller – AT89C51 / AT89S52
📁 Project List
#	Project	Concept Demonstrated
1	LED Blinking	Basic GPIO output, timing delays
2	LED Pattern / Chaser	Port manipulation, loops
3	7-Segment Display Counter	Multiplexing, BCD-to-7-segment
4	LCD Interfacing (16x2)	Parallel data interfacing
5	Keypad Interfacing (4x4)	Matrix scanning, input handling
6	DC Motor Control	Port output, relay/driver interfacing
7	Stepper Motor Control	Sequencing, ULN2003 driver
8	Timer/Counter Application	On-chip timer registers (TMOD, TCON)
9	External Interrupt Demo	INT0/INT1 handling
10	UART Serial Communication	Serial data TX/RX, baud rate setup
11	ADC0808 Interfacing	Analog-to-digital conversion
12	Buzzer/Alarm System	Sensor-triggered output

(Update this table to match the exact projects included in your zip.)

📂 Repository Structure
8051-Proteus-Projects/
├── Project01_LED_Blinking/
│   ├── LED_Blinking.pdsprj
│   ├── main.c
│   └── main.hex
├── Project02_LED_Chaser/
│   ├── LED_Chaser.pdsprj
│   ├── main.c
│   └── main.hex
├── ...
└── README.md
⚙️ How to Run a Project
Open the .pdsprj file in Proteus Design Suite.
Compile the corresponding .c file in Keil µVision to generate the .hex file (already included, but recompile if you make changes).
Load the .hex file into the microcontroller in Proteus (double-click the MCU → Program File → select .hex).
Run the simulation.
🔌 Common Connections
Crystal Oscillator: 11.0592 MHz (standard for UART baud rate accuracy)
Reset Circuit: RC reset on pin 9
Power Supply: 5V DC
👩‍💻 Author

Olivia Thommana Final Year, Computer Science and Engineering Christ College of Engineering, Irinjalakuda

📄 License

This repository is for academic and educational purposes.
