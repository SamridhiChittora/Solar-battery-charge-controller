Solar Battery Charge Controller


Project Description

This project focuses on the design and implementation of a solar battery charge controller that regulates the power from a solar panel to ensure safe and efficient battery charging. The controller protects the battery from overcharging, deep discharging, and excessive current, thereby improving battery lifespan and system reliability.
The system is built using discrete components such as voltage regulators, transistors, diodes, and relays to control the charging process. This cost-effective solution can be used in applications like solar home systems, portable power solutions, and other off-grid renewable energy systems.

Components 
A list of necessary components required to carry out the design on this project are as follows: 
1. LM317 
It is a 3-terminal adjustable voltage regulator which can supply an output voltage adjustable from 1.2V to 37V.

2. LM7812  
It is a fixed linear voltage regulator integrated circuit. It produces a voltage that is positive relative to a common ground.

3. LM358  
Used for voltage comparison to monitor battery levels and control charging states. It compares reference voltage with battery voltage to activate or deactivate charging.

4. Relay  
Automatically disconnects the battery when fully charged or reconnects when voltage drops below a threshold. 
Other components used in this circuit are solar panels, 12V rechargeable battery, diodes, filter capacitor, Zener diodes, resistors, transistors and indicators (LEDs)


Working Principle
The solar charge controller circuit consists of four main stages: current booster, battery level indicator, battery charge controller, and power supply unit.

Current Booster: Uses LM317 Voltage Regulator, a transistor, and blocking diodes to allow maximum current from the solar panel to charge the battery while ensuring proper current flow.

Battery Level Indicator: Implemented using LM358 Operational Amplifier as a comparator to monitor battery voltage and indicate the battery charge level using LEDs.

Battery Charge Controller: A comparator and relay automatically disconnect the battery from charging when it becomes fully charged, preventing overcharging.

Power Supply Unit: A LM7812 Voltage Regulator provides a stable 12V supply to the comparator circuits for reliable operation.

Circuit diagram
<img width="801" height="744" alt="image" src="https://github.com/user-attachments/assets/11f1c3d2-ec8f-4f92-8515-5510caa49e75" />
