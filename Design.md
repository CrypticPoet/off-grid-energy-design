# ELP305 Design and Systems Laboratory
## Semester 2, 2021-2022 
### Tribe E

# 3. SUNERGY Design
_The GitHub repository that our tribe is using is linked [here](https://github.com/CrypticPoet/off-grid-energy-design)_ [1].

In the following document, we give a brief on how the off-grid energy solution is expected to look like after assembling the various components. We also give design blueprints and wiring diagrams wherever required, making necessary but plausible assumptions about the geography and architecture of the house.

**NOTE:** Some specifications have been changed after taking the design into consideration. These updated requirements/specifications are available in the GitHub repository.

---

##### Table of Contents:
- [3. **SUNERGY Design**](#3-sunergy-design)
  - [3.1 **CAD/Assembly**](#31-cadassembly)
  - [3.2 **Wiring Diagram**](#32-wiring-diagram)\
  - [3.3 **Documentation Statistics**](#33-documentation-statistics)
  - [3.4 **Document Readability indices**](#34-document-readability-indices)
  - [3.5 **References**](#35-references)

---

## 3.1 CAD/Assembly
The following image is the 3-D diagram of the designed house.
<p align="center">
	<img src="https://raw.githubusercontent.com/CrypticPoet/off-grid-energy-design/master/CAD%20Design/front%20view.png" alt="Front View" width=500>
	<figcaption align="center">Fig 3.1.1: Front View</figcaption>
</p>

---

<p align="center">
	<img src="https://raw.githubusercontent.com/CrypticPoet/off-grid-energy-design/master/CAD%20Design/side%20view.png" alt="Side view" width=300/> 
	<img src="https://raw.githubusercontent.com/CrypticPoet/off-grid-energy-design/master/CAD%20Design/back%20view.png" alt="Back View" width=300/>
	 <figcaption align="center">Fig 3.1.2: Side View and Back View (L to R)</figcaption>
</p>

---

<p align="center">
	 <img src="https://raw.githubusercontent.com/CrypticPoet/off-grid-energy-design/master/CAD%20Design/tinker.jpeg" alt="Isometric view"  width=300/> 
	 <figcaption align="center">Fig 3.1.3: Isometric View</figcaption>
</p>

---

The components of our energy solution are detailed as follows:

<p align="center">
	<img src="https://raw.githubusercontent.com/CrypticPoet/off-grid-energy-design/master/CAD%20Design/side%20cut.png" alt="Side Cut view" width=300/> 
	<img src="https://raw.githubusercontent.com/CrypticPoet/off-grid-energy-design/master/CAD%20Design/back%20cut.png" alt="Back Cut View" width=300/>
	<figcaption align="center">Fig 3.1.4: Component Labels</figcaption>
</p>

***Label 1*** - Solar Panels  
Solar panels to take the solar energy and give a DC current.

***Label 2*** - Inverter  
Takes the solar DC current and supply it power supply as well as store it in battery.

***Label 3*** - Battery  
Stores the solar converted electrical energy for further use when solar power cannot be harnessed e.g. Night. 

---

## 3.2 Wiring Diagram
The next step is to realize the design using all the components mentioned in the specifications by appropriately connecting them. The diagram below shows the connections for the same. 

<p align="center"><img src="https://raw.githubusercontent.com/CrypticPoet/off-grid-energy-design/master/Images/wiring_diagram.jpg" width=512></p>

The solar panels are connected in a 2x2 fashion using the MC4 Panel Connectors. These are then connected to a DC Circuit Breaker using T4 connectors. The wires then go via a DC Surge Protector to the invertor which is connected to a series combination of 3 batteries of 12V each. The output of the invertor then goes to an AC circuit breaker which has also been connected to the generator for backup. This is finally connected to the MCB inside the house.

---
