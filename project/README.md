## Autonomous Two Wheeled Vehicle

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Sources](#sources)

## General info
The two wheeled autonomous self-balancing vehicle original prototype was developed by a mechatronics student group at UNC Charlotte mechanical engineering department group in the fall semester of 2018. It was designed to self-balance itself and be controlled wirelessly via an Arduino joystick. The system was powered by two 24V 82.88Wh Lithium-ion battery with dual outputs of 24V and 12V. The two 24V outputs were connected in series to create a bi-polar power source of peak voltage of +-24V to power the amplifier circuit and the 12V in series to (not bipolar) to power the myRIO. The myRIO embedded device was used as a controller to compute desired control target difference and output control signals to compensate appropriately. 
The main objective of this project was improving on the previous designs done by the prior group in the design and implementation of a two wheeled self-balancing non-autonomous vehicle prototype. The current team was tasked with the following:

* Hardware
  - Design and install new power amplifier circuit.
  - Design and install new mounts for DC motors.
  - Procure and test new charger for the onboard batteries.
  - Procure and install new motors.
  - Test the rest of the hardware systems within the prototype.
  
* Software
  - Install NI LabVIEW.
  - Install myRIO drivers.
  - Create dashboard in LabVIEW for controlling motors and reading sensor data.
  - Verify wireless connection stable wireless connection.
  
* Mechanical system derivation and controller setup 
  - Derive the Lagrangian mechanics of the system.
  - Develop a control strategy.
	
## Technologies
Project is created with:
* NI-LabVIEW v19.0f2
* KiCAD v5.1.10
* Autodesk Inventor version 24 Siena
* Python 3.7


## Sources
View the full report the [manual here](https://drive.google.com/drive/folders/1hvE5-GHNWjqRfQ4K0hiLiVEb_eAEkb54?usp=sharing).
This project is a requirement for the MEGR7222 Mechatronics Course at the University of North Carolina, Charlotte.
