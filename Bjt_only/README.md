\# Automatic Light-Sensing LED Switch (Dark Sensor)



This project is a Proteus simulation of a simple, analog automatic light-sensing circuit. It uses a Light Dependent Resistor (LDR) to detect ambient light levels and controls an LED indicator using an NPN transistor as a switch.



The pink LED turns \*\*ON\*\* automatically when the environment gets dark and turns \*\*OFF\*\* when sufficient light is detected by the LDR.



!\[Circuit Diagram](Place\_Your\_Image\_Link\_Here)

> \*Figure 1: Schematic Diagram in Proteus\*



\## ⚙️ Key Features

\* \*\*Automatic Detection:\*\* Activates the output purely based on ambient light intensity without manual intervention.

\* \*\*Analog Design:\*\* Built using discrete components (transistor, resistors, LDR) with no microcontroller programming required.

\* \*\*9V Operation:\*\* Designed to run on a standard 9V DC power source.



\## 🛠 Tools Used

\* \*\*Simulation Software:\*\* Proteus Design Suite.



\## 🔧 Bill of Materials (BOM)



Based on the schematic:



| Designator | Component Type | Value / Model | Quantity | Description |

| :--- | :--- | :--- | :--- | :--- |

| Q1 | NPN Transistor | \*\*BC547\*\* | 1 | Main switching element. |

| LDR1 | Sensor | \*\*TORCH\_LDR\*\* | 1 | Light Dependent Resistor (photoresistor). |

| D1 | LED | \*\*Pink\*\* | 1 | Visual output indicator. |

| R1 | Resistor | \*\*100kΩ\*\* | 1 | Forms the voltage divider network with the LDR to bias the transistor base. |

| R2 | Resistor | \*\*330Ω\*\* | 1 | Current limiting resistor for the LED. |

| BAT1 | Power Source | \*\*9V\*\* | 1 | DC Battery. |



\## 🚀 How to Run the Simulation



1\.  Clone this repository to your local machine.

2\.  Open the `.pdsprj` project file in \*\*Proteus Design Suite\*\*.

3\.  Press the \*\*Run Simulation\*\* (Play) button at the bottom-left corner.

4\.  \*\*Interact:\*\* To test the circuit, move the interactive "Torch" light source away from or closer to the `LDR1` component in the simulation to simulate dark and light conditions, respectively.



\## 👤 Author

\* \*\*\[Your Name]\*\* - \*Circuit Design \& Simulation\*



---

\*This project is for educational purposes, demonstrating basic transistor switching and sensor applications.\*

