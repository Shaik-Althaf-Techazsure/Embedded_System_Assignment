# Embedded_System_Assignment

**Project Overview**

This repository contains the solution to a three-part embedded systems assignment. The project demonstrates core skills in microcontroller programming, analog circuit design, and the analysis of electrical engineering principles. All solutions were developed and validated through simulation, showcasing a comprehensive understanding of both theoretical concepts and practical application.

**Assignment Details**

The assignment consists of three main questions, each addressing a different aspect of embedded systems design:

Q1: Dynamic LED Pattern Control: A C++ program for the Raspberry Pi Pico that controls an LED blinking pattern based on time and a push-button toggle. The solution is non-blocking and uses a state-machine approach.

Q2: PWM Signal Conditioning: A two-stage analog circuit simulated in Proteus that performs DC level-shifting on a PWM signal, first centering it around 0V and then shifting it back to the original voltage range.

Q3: Battery Pack Topologies: A simulation-based analysis of the pros and cons of different battery pack configurations to meet specific voltage and capacity requirements.

**Hardware and Software**

Microcontroller: Raspberry Pi Pico W (RP2040)

Simulation Tools: Wokwi (for Q1), Proteus (for Q2 & Q3)

Programming Language: C++ (with the Arduino framework)

Key Concepts: Non-blocking timing, GPIO control, Analog circuit design, PWM, Op-amps, Battery management.


**Project Structure**

Q1/: Contains the C++ source code for the Raspberry Pi Pico project.

Q2/: Contains the Proteus project files for the PWM level-shifting circuits.

Q3/: Contains the Proteus project files for the battery pack simulations

**Setup and Usage**

To view the projects, you can use the respective simulation software:

Q1: Open the Q1.ino file in the Arduino IDE with the Raspberry Pi Pico board package installed, or simply copy the code into a Wokwi project and run the simulation.

Q2 & Q3: Open the .pdsprj files in Proteus to view the schematic and run the simulations.

**Simulation Results**

Below are the key outputs from the simulations, which validate the correct operation of each project.

Q1: LED Pattern Control
The Wokwi simulation shows the correctly wired circuit and the code running, demonstrating the dynamic LED pattern control.

<img width="1916" height="958" alt="Q1 Raspberry pi_Pico_LED_Pattern" src="https://github.com/user-attachments/assets/a5f3bf70-2b3d-4440-9a0f-665cbde85e8e" />


Q2: PWM Signal Conditioning
The Proteus oscilloscope output demonstrates the successful level-shifting of the PWM signal. The input signal (0-3.3V) is first shifted to -1.65V to +1.65V and then shifted back to its original range.

<img width="1285" height="1077" alt="Q2 Circuit 1 Down-Shifting Circuit (RC High-Pass Filter)" src="https://github.com/user-attachments/assets/584e7939-eb01-478b-b9da-4f53865e51b5" />

<img width="1918" height="1078" alt="Q2 Circuit 1 Down-Shifting Circuit (RC High-Pass Filter)_OUTPUT" src="https://github.com/user-attachments/assets/cc1c4374-278d-4fa3-817e-6a1c9d367b8e" />

<img width="1918" height="1078" alt="Q2 Circuit 2 Up-Shifting Circuit (Op-Amp Level Shifter)" src="https://github.com/user-attachments/assets/dd553127-5ce9-4dea-b705-a6b267191808" />

<img width="1918" height="1078" alt="Q2 Circuit 2 Up-Shifting Circuit (Op-Amp Level Shifter)_OUTPUT" src="https://github.com/user-attachments/assets/454a36ad-4429-49c9-8578-be4f7faf152e" />


Q3: Battery Pack Topologies
The Proteus simulation for the battery pack topologies shows the total voltage and current for each configuration, confirming their characteristics.

<img width="1918" height="1078" alt="Q3 Topology 1 Series_Parallel_With Load" src="https://github.com/user-attachments/assets/035b351b-dd4e-460e-81d3-1eea07eb84cf" />

<img width="1073" height="1078" alt="Q3 Topology 1 Series_Parallel_Without Load" src="https://github.com/user-attachments/assets/42b7f417-07eb-4802-8f79-ca29e156dc8e" />

<img width="1918" height="1078" alt="Q3 Topology 2 Parallel_without Load" src="https://github.com/user-attachments/assets/633ab43c-b32f-468e-8144-f29a9ac8eeea" />

<img width="1915" height="1077" alt="Q3 Topology 2 Parallel_with Load" src="https://github.com/user-attachments/assets/1fbe574a-90e6-45fb-b2a5-ce6dff5e2e50" />

