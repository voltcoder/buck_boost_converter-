# buck_boost_converter-simulation separately
Simulation of a Buck-converter and Boost-converter using MATLAB/Simulink for studying DC-DC power conversion.
As the name suggest this repository consist of separate models.

# Buck and Boost Converter Simulation using MATLAB/Simulink

## Project Overview
This project presents the modeling and simulation of **Buck Converter** and **Boost Converter** using **MATLAB/Simulink**.  
These DC–DC converters are fundamental power electronics circuits used to step voltage **down (buck)** or **up (boost)** based on application requirements.

The simulations demonstrate the working principle, voltage conversion, and current behavior of both converters under PWM control.

---

## Objectives
- To model Buck and Boost DC–DC converters in Simulink  
- To understand step-down and step-up voltage operation  
- To analyze output voltage and inductor current  
- To gain practical understanding of DC–DC converters used in EVs and power supplies  

---

## Tools & Software Used
- MATLAB  
- Simulink  
- Simscape Electrical  

---

## System Description

### Buck Converter
- Steps down the input DC voltage  
- Uses a controlled switch, diode, inductor, and capacitor  
- Output voltage is lower than input voltage  

### Boost Converter
- Steps up the input DC voltage  
- Inductor stores energy during switch ON time  
- Output voltage is higher than input voltage  

PWM signals are used to control the switching operation in both converters.

---

## Observed Parameters
- Input Voltage (Vs)  
- Output Voltage (Vo)  
- Inductor / Load Current  
- Switching Pulse (PWM)  

---

## How to Run the Simulation
1. Open **MATLAB**
2. Set the project folder as the working directory
3. Open the required Simulink file:
   - `buck_converter.slx`
   - `boost_converter.slx`
4. Click **Run**
5. Observe voltage and current waveforms on scopes and displays

---

## Results
- Buck converter successfully reduces input voltage  
- Boost converter successfully increases input voltage  
- Stable current and voltage waveforms observed  
- Proper PWM-based switching operation achieved  

---

## Applications
- Electric Vehicles (EVs)  
- DC Power Supplies  
- Battery Charging Systems  
- Renewable Energy Systems  

---

## Future Improvements
- Closed-loop voltage control using PI controller  
- Efficiency and ripple analysis  
- Hardware implementation using MOSFET and driver circuits  
- Integration with battery or motor load  

---

## Author
**Swati Sharma**  
Electrical Engineer | Power Electronics | EV Systems  

---

## Note
This project is developed for academic and learning purposes to understand basic DC–DC converter operation. 
