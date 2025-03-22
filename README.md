# Exp_ No: 01 - Design & Implementation of CMOS Inverter Design Using Cadence EDA Tools

## Aim
The aim is to create and simulate a CMOS inverter circuit with Cadence EDA tools, assess its key electrical properties, and explore foundational CMOS principles, including the design workflow and simulation approaches.

## Tools Required

### Cadence EDA Suite
- **Virtuoso Schematic Editor** (for circuit design)  
- **Spectre Simulator** (for circuit simulation)  

### Process Design Kit (PDK)
- CMOS technology library (e.g., 180nm, 45nm node)  

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure:
### 1. Launch Cadence Virtuoso Environment:
     Open the Cadence Virtuoso tool and set up the working library.
     Create a new schematic cell view for the CMOS Inverter design.
### 2. Schematic Design:
    Select the NMOS and PMOS transistors from the library.
    Connect the NMOS transistor with its source terminal to GND and its drain terminal to the output node.
    Connect the PMOS transistor with its source terminal to VDD and its drain terminal to the same output node as NMOS.
    Join the gate terminals of both transistors to form the input node.
    Connect input voltage sources Vdc and Vpulse
### 3. Simulation:
    Check the Design for Errors and proceed for Simulation
    Launch the Analog Design Environment (ADE).
    Configure transient analysis for time-domain response.
    Set the simulation parameters such as voltage sweep range and step size.
    Use Spectre simulator to perform transient and DC analyses.
### 4. Waveform Analysis:
    Observe the output voltage waveform concerning the input voltage.

## Circuit Diagram:
#### 1. Schematic of CMOS Inverter:

   ![WhatsApp Image 2025-03-21 at 08 53 33_db631dd7](https://github.com/user-attachments/assets/82cd4e16-4eda-4e1e-b539-c17ed6e0cd59)
#### 2. Transient Response Setup:

    ![WhatsApp Image 2025-03-21 at 09 02 29_d2fb4376](https://github.com/user-attachments/assets/9a6896be-1b5b-413d-b765-e86df6d5399e)

#### 3. Voltage Transfer Characteristic (VTC)  Setup:

   ![WhatsApp Image 2025-03-21 at 08 53 33_81dc4d46](https://github.com/user-attachments/assets/6b773fa9-dfdd-4dd6-84c7-3e2506e82285)
   
## Output
#### 1.Transient Analysis Output

  ![WhatsApp Image 2025-03-21 at 08 53 34_84dfe3bf](https://github.com/user-attachments/assets/3f90ac18-07c4-49d5-8b56-ea16d94f8bf9)

#### 2.DC Analysis Output

![WhatsApp Image 2025-03-21 at 08 53 34_97824227](https://github.com/user-attachments/assets/b7a8e582-d7dc-4ed6-85ae-1bf88403fcf8)

## Results:

1.	Successfully designed the CMOS inverter schematic using Cadence EDA tools.
2.	The simulation results demonstrated the correct logic operation of the inverter, where the output voltage switches between high (Vdd) and low (0V) levels, corresponding to the input voltage transitions.
3.	The Voltage Transfer Characteristic (VTC) curve was plotted, showing the relationship between input and output voltages.











