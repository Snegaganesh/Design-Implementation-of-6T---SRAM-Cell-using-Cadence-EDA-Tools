![Screenshot 2025-03-28 135852](https://github.com/user-attachments/assets/b5b0c747-5e03-4f3a-b96b-0b0bb9c106ba)# Ex No: 04 - Design & Implementation of 6T SRAM Cell Using Cadence EDA Tools

## Aim
The aim is to design and implement a 6T SRAM (Static Random-Access Memory) cell using Cadence EDA tools and verify its functionality through transient analysis simulation.

## Tools Required

### Cadence EDA Suite
- **Virtuoso Schematic Editor** (for circuit design)
- **Spectre Simulator** (for circuit simulation)

### Process Design Kit (PDK)
- CMOS technology library (45nm node)  

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure:
### 1. Launch Cadence Virtuoso Environment:
   - Open the Cadence Virtuoso tool and set up the working library.
   - Create a new schematic cell view for the 6T SRAM cell design.

### 2. Schematic Design:
   - Select NMOS and PMOS transistors from the library.
   - Construct the 6T SRAM cell with two cross-coupled inverters and access transistors.
   - Connect the wordline (WL), bitlines (BL, BLB), and power supply connections.

### 3. Simulation:
   - Check the design for errors and proceed with simulation.
   - Launch the Analog Design Environment (ADE).
   - Perform transient analysis to verify read and write operations.
   - Set up input stimulus and analyze the output waveform.

## Circuit Diagram

![Screenshot 2025-03-24 122239](https://github.com/user-attachments/assets/c22930fc-f396-4787-807d-51088ad7959e)


## 6T SRAM Truth Table

![Screenshot 2025-03-24 123041](https://github.com/user-attachments/assets/29a8a036-d65d-4a25-ba18-3f1f0e358576)


## Schematic Diagram

#### 1. Schematic of 6T SRAM Cell:

   ![Screenshot 2025-03-28 135949](https://github.com/user-attachments/assets/2024a054-0ac2-4941-9578-16d313a1a840)



   ![image](https://github.com/user-attachments/assets/c28aea2b-9e73-48e6-abdb-11c430321b86)


## Output
#### 1. Transient Analysis Output:

   ![Screenshot 2025-03-28 135915](https://github.com/user-attachments/assets/d2807ffe-0973-4d69-a4f4-23b24aa81741)


   ![Screenshot 2025-03-28 135852](https://github.com/user-attachments/assets/74c5f62f-4cf8-4c99-bbd9-e616ec9a29d3)




## Results:
1. Successfully designed the 6T SRAM cell schematic using Cadence EDA tools.
2. Performed transient analysis, verifying the read and write operations of the SRAM cell.
3. Observed correct switching behavior in response to control signals.


