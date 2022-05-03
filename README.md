# Capstone: Lightweight, Long Lasting Power Supply for High Energy Lasers

The motivation for this project is to develop a small-scale lightweight power supply that could eventually be scaled up in size to power the laser for the Army Stryker Vehicle. This power supply will model the actual inputs and outputs of the laser for the Stryker vehicle. This includes looking at the type of drive (current or voltage), the load profile of the laser, acceptable regulation on the output, any output limiters to prevent damage, and types of controllers. Instead of a 50KW laser, we will scale down to a 1 W laser and model our prototype off this. 

Description: As the Army is starting to implement laser systems on Stryker vehicles, the need for a lightweight power supply (LWPS) arose to help fuel this new weapon. For this power supply, a balance of various supply sources utilizes the power density of capacitors and the longevity of a portable battery in a lightweight yet durable configuration. This project’s purpose is to design, fabricate, test, and evaluate the power system for feasibility and efficiency to eventually be scaled up and utilized on these Stryker systems. 


The prototype must model the most effective way to power the Stryker laser. The prototype will be based off what type of laser it is (outputs) and the charging availability (inputs). Using the product owner, advisor input, and revised documents, we will provide a prototype to be tested using a lower-scale laser. 

Features: 
  **Microcontroller Display:** Features an easy-to-use graphic user interface that can monitor current output values for currents, voltages, and power for the entire system.

  **Prototype Operational Requirements: ** Output power of 378mW with a 90% efficiency from energy discharged over the energy input, and a run time of 120 seconds with a recharge period of 280 seconds.

  **Physical Constraints:** 3.3V operating voltage with 150mA-180mA operating current for the laser load. Total weight less than 3kg. 

  **Hybrid Power Supply:** Circuit design uses the battery power source to charge the super capacitors to ensure laser run with minimum downtime, minimizing weight instead of using one larger battery.

  **Microcontroller Communications:** Digital I/O and A/D conversions with relay modules, LCD module, current and voltage sensors, and AC to DC converters. 

Outcomes:

  Efficient Hybrid Power Supply: Both battery power and capacitor sources can work in     
  tandem to effectively regulate the laser system better than a single source alone.

  Lightweight yet Friendly: GUI puts the user in control of the power systems while         
  maintaining the lightweight and durable requirement necessary for Army vehicles and       
  combat scenarios. 

  Upscale Ability: Project’s input and output requirements can be upscaled to match        
  requirements by the Stryker system. 


**Operational Requirements:**

Rated Output Power (optical): 100mW 

Optical Efficiency: >=30% 

Run Time: 120 seconds

Recharge Time: 280 seconds

Weight <= 3kg

**Constraints:**

$1,000 budget 

Available Supercapacitors

3.8V Maximum Voltage

60 Farads/unit

Rated Current: 150mA/unit


Members of Team: Pawat Promraksa, Maxwell McKendry, Andres Rodriguez, Rebecca Syrup

Instructors: COL Ingold

Advisors: Dr. St. Leger, LTC Babbitt

