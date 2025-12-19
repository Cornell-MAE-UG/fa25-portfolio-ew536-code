---
layout: project
title: Thermofluid System Analysis
description: Heat Exchanger Analysis
image: /assets/images/heatEXCHgoogle.jpg
---
Heat exchangers are widely used in real-world applications to control temperature for efficiency and safety. They are part of power generation, heating and cooling, and industrial processes and enable the transfer of thermal energy between fluids at different temperatures without direct mixing. In this project, a heat exchanger was run in different modes and analyzed experimentally to evaluate its thermal performance and to assess the validity of common thermodynamic assumptions, including steady-state and adiabatic operation.

## Setup
A lightly-guided, hands-on experimental setup was provided, consisting of a heat exchanger connected to four water buckets driven by pumps. Temperature measurements were taken from the water buckets. 
![Photo of setup]({{ "/assets/images/hxch-setup.jpg" | relative_url }}){: .setup-image style="width: 500px"}

Supplies used:  
• one heat exchanger  
• two water pumps  
• 4 water buckets  
• ice (to keep cold water source cold)  
• water  
• styrofoam for insulation (for the cold water source)  
• an immersion heater (for the hot water source)  
• one thermocouple  
• four thermometers  
• food dye (for visually distinguishing flow)  
  A cross section of the heat exchanger used is provided below; metal plates conduct heat between the parallel pipes.  
  
![Photo of heat exchanger]({{ "/assets/images/hxch-cross-section.jpg" | relative_url }}){: .setup-image style="width: 500px"}

## Analysis
Typically, several assumptions that do not reflect reality are made to simplify thermodynamic analysis. The system, defined as the volume within the heat exchanger, is ideally an adiabatic control volume, with all heat lost by the hot fluid transferred to the cold fluid. However, because the heat exchanger has internal thermal resistance, some of the heat is transferred to the heat exchanger itself. 
Additionally, the actual system is not truly at steady-state, which requires constant inlet and outlet temperatures, mass flow rate, and heat transfer rate. During startup and shutdown, the system is not at steady-state. Inlet and outlet temperatures are not constant because the water buckets were open to the air; the hot water source loses heat to the environment, and the cold water source gains heat.    
  
The heat exchanger was set up in parallel and in counterflow.  Note that "0" and "f" subscript denote initial and final conditions of the fluid, "i" and "f" denote "inlet" and "exit", and "CV" denotes "control volume".  Control-volume steady-state operation is assumed:
**In parallel:**
![Analysis in Parallel]({{ "/assets/images/hxch-parallel.jpg" | relative_url }}){: .setup-image style="width: 500px"}

The negative Q'CV indicates loss of heat to the environment and therefore non-adiabatic operation. Entropy generation is more negative in the non-adiabatic case (with Q'/T term) under the steady state assumption because some entropy is carried out of the system as heat dissipated into the exchanger.

**In counterflow:**
![Shaded rendering of earlier version]({{ "/assets/images/radio-machine.jpg" | relative_url }}){: .inline-image-r style="width: 200px"}

![Photo of old radio]({{ "/assets/images/old-radio.jpg" | relative_url }}){: .inline-image-l}





