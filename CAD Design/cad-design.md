## 3.1 CAD/Assembly
The following image is the 3-D diagram of the designed house.
<p align="center">
	<img src="https://raw.githubusercontent.com/CrypticPoet/off-grid-energy-design/master/CAD%20Design/home_wireframe_front.jpg" alt="Front View" width=500>
	<figcaption align="center">Fig 3.1.1: Front View</figcaption>
</p>

<p align="center">
	<img src="https://raw.githubusercontent.com/CrypticPoet/off-grid-energy-design/master/CAD%20Design/home_wireframe.jpg" alt="Side view" width=500/> 
	 <figcaption align="center">Fig 3.1.2: Side View</figcaption>
</p>

<p align="center">
	 <img src="https://raw.githubusercontent.com/CrypticPoet/off-grid-energy-design/master/CAD%20Design/home_wireframe_top.jpg" alt="Top View" width=500/>
	 <figcaption align="center">Fig 3.1.3: Top View</figcaption>
</p>

<p align="center">
	 <img src="https://raw.githubusercontent.com/CrypticPoet/off-grid-energy-design/master/CAD%20Design/home_orthographic.jpg" alt="Isometric view"  width=500/> 
	 <figcaption align="center">Fig 3.1.3: Orthographic View</figcaption>
</p>


The components of our energy solution are detailed as follows:

***Label 1*** - Solar Panels
Solar panels to take the solar energy and give a DC current.

<p align="center">
	<img src="https://raw.githubusercontent.com/CrypticPoet/off-grid-energy-design/master/CAD%20Design/solar_side.jpg" alt="Side view" width=300/> 
	<img src="https://raw.githubusercontent.com/CrypticPoet/off-grid-energy-design/master/CAD%20Design/solar_front.jpg" alt="Front View" width=300/>
	<img src="https://raw.githubusercontent.com/CrypticPoet/off-grid-energy-design/master/CAD%20Design/solar_top.jpg" alt="Top View" width=300/>
	<figcaption align="center">Fig 3.1.4: Side View, Front View and Top View (L to R)</figcaption>
</p>

***Label 2*** - Inverter  
Takes the solar DC current, and supply it power supply as well as store it in battery.

<p align="center">
	<img src="https://raw.githubusercontent.com/CrypticPoet/off-grid-energy-design/master/CAD%20Design/inverter_side.jpg" alt="Side view" width=300/> 
	<img src="https://raw.githubusercontent.com/CrypticPoet/off-grid-energy-design/master/CAD%20Design/inverter_front.jpg" alt="Front View" width=300/>
	<img src="https://raw.githubusercontent.com/CrypticPoet/off-grid-energy-design/master/CAD%20Design/inverter_top.jpg" alt="Top View" width=300/>
	<figcaption align="center">Fig 3.1.5: Side View, Front View and Top View (L to R)</figcaption>
</p>

***Label 3*** - Battery  
Stores the solar converted electrical energy for further use when solar power cannot be harnessed e.g. Night. 

<p align="center">
	<img src="https://raw.githubusercontent.com/CrypticPoet/off-grid-energy-design/master/CAD%20Design/battery_side.jpg" alt="Side view" width=300/> 
	<img src="https://raw.githubusercontent.com/CrypticPoet/off-grid-energy-design/master/CAD%20Design/battery_side.jpg" alt="Front View" width=300/>
	<img src="https://raw.githubusercontent.com/CrypticPoet/off-grid-energy-design/master/CAD%20Design/battery_top.jpg" alt="Top View" width=300/>
	<figcaption align="center">Fig 3.1.5: Side View, Front View and Top View (L to R)</figcaption>
</p>

---

## 3.2 Wiring Diagram
The next step is to realize the design using all the components mentioned in the specifications by appropriately connecting them. The diagram below shows the connections for the same. 

<p align="center" id="wiring"><img src="https://raw.githubusercontent.com/CrypticPoet/off-grid-energy-design/master/Images/wiring_diagram.jpg" width=512></p>

The solar panels are connected in a 2x2 fashion using the MC4 Panel Connectors. These are then connected to a DC Circuit Breaker using T4 connectors. The wires then go via a DC Surge Protector to the invertor which is connected to a series combination of 3 batteries of 12V each. The output of the invertor then goes to an AC circuit breaker which has also been connected to the generator for backup. This is finally connected to the MCB inside the house.

---