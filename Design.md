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
  - [3.2 **Wiring Diagram**](#32-wiring-diagram)
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

## 3.3 Documentation Statistics
%%Needs to be changed%%

| Word Count | # unique words | # repeated words | # sentences | # characters | # characters w/o spaces | # syllables |
|------------|----------------|------------------|-------------|--------------|-------------------------|-------------|
| 434        | 922            | 1715             | 11          | 3592         | 3204                    | 941         |

| Avg # words per sentence | Avg # characters per sentence | Avg # characters per word | Avg # syllables per word |
|--------------------------|-------------------------------|---------------------------|--------------------------|
| 40                       | 327                           | 7.4                       | 2.16                     |

The above results were obtained using https://wordcounter.net/ [7].

---

## 3.4 Document Readability indices
%%Needs to be changed%%

| Readability Index                | Score |
|----------------------------------|-------|
| Flesch Reading Ease score        | 61    |
| Dale-Chall Readability score     | 8.8   |
| Flesch-Kincaid Grade level       | 7     |
| The Coleman-Liau Index           | 14    |
| Automated Readability Index      | 11    |
| SMOG Formula score               | 12    |
| Spache Readability score         | 4     |

The above scores were obtained using Visual Studio Code extension called Readability Check [8] by jemcclin.

---

## 3.5 References

[1] [GitHub - Off Grid Energy Design - Tribe E](https://github.com/CrypticPoet/off-grid-energy-design)

[2] [600 Watt Solar Panel Wiring Diagram & Kit List](https://mowgli-adventures.com/600-watt-solar-panel-wiring-diagram/)

[3] [Application of  DC600V/20kA Photovoltaic Surge Protector for Solar Power System/PV Solar SPD](https://sc01.alicdn.com/kf/HTB1CF0DHFXXXXaiXXXXq6xXFXXXB/201135244/HTB1CF0DHFXXXXaiXXXXq6xXFXXXB.jpg_.webp)

[4] [Factory Customized High Efficient T4 Solar Connector](https://image.made-in-china.com/44f3j00sfSTKWnPEyrL/Dsola-Factory-Customized-High-Efficient-T4-Solar-Connector.jpg)

[5] [How to Connect a Portable Generator to the Home Supply - 4 Methods](https://www.electricaltechnology.org/2013/11/how-to-connect-portable-generator-to-home-supply.html)

[6] [Solarverter PRO PCU Installation | Luminous India](https://www.youtube.com/watch?v=BmDQkVR5orU)

[7] [WordCounter - Count Words & Correct Writing](https://wordcounter.net/)

[8] [Readability Check - Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=jemcclin.readabilitycheck)

---