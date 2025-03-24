# Exp_MG No: 01 - Design & Implementation of CMOS Inverter Design Using Cadence EDA Tools
JAYA VISHAL M
212223060102
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
![1](https://github.com/user-attachments/assets/f3ff729b-07df-492d-8c78-25c6e5705465)

  
#### 2. Transient Response Setup:
![3](https://github.com/user-attachments/assets/7b929486-2b7d-4b68-882a-f2f6fb6f3d0d)

    
#### 3. Voltage Transfer Characteristic (VTC)  Setup:

  ![2](https://github.com/user-attachments/assets/70e1d6fd-93a3-4837-a135-593fad4c041a)

   
## Output
#### 1.Transient Analysis Output

 ![WhatsApp Image 2025-03-24 at 08 28 34_dc1232ef](https://github.com/user-attachments/assets/7b4bb6f8-5721-4c93-af88-b15b2db93c4a)

#### 2.DC Analysis Output

![4](https://github.com/user-attachments/assets/e8b41ec7-3a98-4117-9b5a-b7dec8236ae0)

## Results:

1.	Successfully designed the CMOS inverter schematic using Cadence EDA tools.
2.	The simulation results demonstrated the correct logic operation of the inverter, where the output voltage switches between high (Vdd) and low (0V) levels, corresponding to the input voltage transitions.
3.	The Voltage Transfer Characteristic (VTC) curve was plotted, showing the relationship between input and output voltages.











