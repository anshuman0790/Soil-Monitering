
# eYRC-21-Soil-Monitoring-Bot-Theme
Soil is at the heart of agriculture and its quality directly affects the quality of the yield. While soil is regarded as the “fertile substrate” for agriculture, it is important to understand that a balance among mineral components, soil organic matter, air and water is essential for soil to make it suitable for agriculture.

The theme Soil Monitoring Bot (SM), as the name suggests this comprises a robot deployed to monitor the soil conditions within an agriculture field divided into various farmlands. The robot swiftly navigates through them and monitors the soil condition. It then goes to the storage unit and supplies the necessary mineral, nutrients, organic matter, etc. as required by the soil.

In this theme, the team will build the SM Bot to deploy it on an arena that is the abstraction of the agriculture field. The brain of the robot is powered by an FPGA (Field Programmable Gate Array) that controls its sensors, actuators and pick-place mechanism.

Major challenges and learnings in this theme include building the Soil Monitoring Bot from scratch using an FPGA. This FPGA based robot will be able to traverse the arena, sense the environment and pick-and-place the necessary supplies from the supply unit to the field. It will also use wired and wireless communication techniques. This theme will help teams build a sophisticated architecture using Verilog HDL and unveil the powerful parallel processing capabilities of FPGAs.

### Hardware Used 
- De0-Nano board
- 600 rpm N20 motors
- L9110s Motor Driver
- 2S Li-ion battery
- Xbee s2c module
- TCS3200 Color sensor
- Level shifter
- Potentiometer
- Electromagnet
- LEDs 

# Task 0 : Software Installation

1. Introduction & Installation
   
Installing Quartus and ModelSim

Method 1. Download using Complete Software Package (Recommended)

Method 2. Download using Individual Software Package


**Task 0
Welcome to Task 0 of Soil Monitoring Bot!
The aim of this task is to get you started with installation of required software and to learn resources related to the software.**

This task is divided into three parts :

Software Installation

Verifying Installation

Learning Resources

Note :

1. It is recommended in this theme to use Windows 10 OS.
2. We will be using Verilog HDL in the entire theme.

**Software Installation :**

In this step, you will be downloading and installing Quartus Prime 19.1 along with Modelsim and Notepad++ 197. The detailed instructions for installing Quartus Prime and Modelsim are provided in the section Introduction & Installation. For downloading softwares you can use any of the two methods mentioned in the "Introduction & Installation" section depending upon your internet connectivity.

**Verifying Installation:**

In this section you will be verifying if you have properly installed the softwares. Start with Getting started with Quartus section and then proceed with the Verifying Installation section. If your Modelsim simulation output matches with the output shown in below image then installation is successful.

**Learning Resources :**

Refer the following tutorials to get started with the Verilog HDL, Quartus and Modelsim simulation environment.
a. Prerequisites
b. Verilog HDL Tutorials 209
c. Two Way Switch

# Task 1: Design Methodologies of Verilog HDL (SM21)

**Task 1
Welcome to Task 1 of Soil Monitoring Bot!
The objective of this task is to understand the Verilog HDL basics and the design methodologies of Verilog HDL. In this task you have to design combinational and sequential circuits in Quartus Prime and do the RTL simulation in Modelsim.**

Note: You can go back and read Task 0 as it will be a prerequisite for Task 1.

This task is divided into 4 sub-tasks:

Combinational Circuit 540 : The aim is to design a combinational circuit using 4-bit comparator, 4 input logic function and 4:1 multiplexer.

Sequential Circuit 160 : The aim is to design a 3-bit synchronous counter using T flip-flops.

Finite State Machine 113 : The aim is to design a Finite State Machine in Verilog HDL to detect sequence/pattern.

Frequency Scaling and PWM 125 : The aim is to implement frequency scaling in Verilog HDL and also implement Pulse Width Modulation.

# Task 2 : ADC & UART

**Task 2
Welcome to Task 2 of Soil Monitoring Bot
The objective of this task is to study Analog to Digital Converter (ADC) and UART (Universal Asynchronous Receiver Transmitter) communication protocol. Team then implements the given tasks in Quartus Prime and does the RTL simulation in Modelsim.**

Task 2 is divided into 2 sub-tasks:

ADC 301 : The aim is to design a control module which will communicate with on board ADC (Analog to Digital Converter) and fetch the digital output.

UART 130 : The aim is to design a UART (Universal Asynchronous Receiver Transmitter) Transmitter with parameters described in the problem statement.

# Task 3: H/W testing and Bot building

**Task 3
Welcome to Task 3 of Soil Monitoring Bot**

Task 3 is divided into 4 sub-tasks:

Flex Printing : In this task, you have to print the arena.

The following subtasks will be released soon upon hardware shipment.

Arena Preparation : In this task, instructions are given for block making and preparation of the arena.

Hardware Testing : In this task, instructions are given for testing the hardware provided in the robotic kit.

Bot Building : In this task, you will build the SM robot.

# Task 4 - Line Following, Color Sensing & Wireless Communication

**Line Following, Color Sensing & Wireless Communication**

**Objective :**

The objective of this task is to build a robot (SM bot) and make it follow a black line along with color & node detection, and wireless communication using Xbee.

For simplicity, this task can be divided into 4 sub-tasks and then all the sub-tasks can be merged to complete the task 4.

Bot Building

Black Line following

Color Detection (SI Identification)

Wireless Communication using Xbee (UART).

# Task 5 - Interfacing of electromagnet and Path Planning

**Interfacing of electromagnet and Path Planning**

**Objective :**

The objective of this task is to identify SI (Status Indicators) in NG (Nutty Grounds) Farmland, pick Supplies from the Warehouse and deposit in the Farmland at the correct Deposition Zones (DZ).

Note: Before starting the task, refer to the Rulebook.

Following subtasks need to be done in the NG Farmland and Warehouse for the successful completion of the Task 5.

In NG Farmland, identify the SI, turn ON respective color led and send respective messages wirelessly via Zigbee (UART).

Pick Supply (S) from the Warehouse based on the SI identified and send the message via Zigbee.

Deposit the Supply picked up from Warehouse in the DZN1 Deposition Zone (DZ), turn OFF the corresponding LED (LED that was turned ON upon SI Identification) and transmit the message via Zigbee (UART).

# Task 6: Final Theme Implementation


Task 6 is the final task of the competition. In this task you are supposed to demonstrate full theme implementation as per the Rulebook. It is divided into two parts:

Original Configuration : This is mandatory task.

Bonus Configuration : This is optional task.

### Final Image of the Arena

![](SM%231153_Task3A/SM%231153_Task3A.jpeg)

### Final image of the robot

<img width="407" alt="image" src="https://user-images.githubusercontent.com/88222914/156010775-a73febb8-10d0-45f8-a8ae-cda05bcacfdd.png">

### Hardware Used 
- De0-Nano board
- 600 rpm N20 motors
- L9110s Motor Driver
- 2S Li-ion battery
- Xbee s2c module
- TCS3200 Color sensor
- Level shifter
- Potentiometer
- Electromagnet
- LEDs 


## Challenges and Learnings 

- Building the Soil Monitoring Bot from scratch
- Pick-place mechanism using electromagnet
- Wired and Wireless communication using XBEE 
- 3 channel ADC controller for fetching 12-bit digital value of analog signal from on-board ADC128S022.
- Interfaced TCS3200 colour sensor with De0 nano FPGA board to detect RGB colours.
- PID control algorithm to control the movement of the bot.
- Motor speed variation using PWM. 
- Circuit Designing 
- Learnt powerfull parallel processing capabilities of FPGA 
- Learnt Verilog Hardware Modelling Language.
- Learnt Path Planning Algorithms.
