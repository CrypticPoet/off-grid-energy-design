<font size="5"> <center> ELP305 Design and Systems Laboratory </center> </font>
<font size="4"> <center> Semester 2, 2021-2022 </center></font>
<font size="3"> <center> Tribe E </center></font>

# 2. **SUNERGY Specifications**
_The GitHub repository that our tribe is using is linked [here](https://github.com/CrypticPoet/off-grid-energy-design)_ [1].

In the following document, we give a brief on various specifications of the components that we will be using in our off-grid living solution. We also mention their properties and why we have chosen them along with the best quotation available for each component.

**NOTE:** These specifications may change as the design work progresses further.

- [2. **SUNERGY Specifications**](#2-sunergy-specifications)
  - [2.1 **Electrical Specifications**](#21-electrical-specifications)
    - [2.1.1 Battery](#211-battery)
      - [Luminous Red Charge RC 18000 150 Ah battery](#luminous-red-charge-rc-18000-150-ah-battery)
    - [2.1.2 Backup Generator](#212-backup-generator)
    - [2.1.3 Hybrid Solar Inverter (Built in Solar Charge Controller)](#213-hybrid-solar-inverter-built-in-solar-charge-controller)
      - [3KVA/ 36 V off Grid Solar Inverter](#3kva-36-v-off-grid-solar-inverter)
      - [Solar Charge Controller](#solar-charge-controller)
        - [Sizing](#sizing)
        - [Required Ratings](#required-ratings)
    - [2.1.4 High Efficiency Solar Panels](#214-high-efficiency-solar-panels)
    - [2.1.5 Wires](#215-wires)
      - [Solar DC Cable](#solar-dc-cable)
      - [Household connection wires](#household-connection-wires)
    - [2.1.6 Safety Measures](#216-safety-measures)
      - [AC Circuit Breaker](#ac-circuit-breaker)
      - [DC Circuit Breaker](#dc-circuit-breaker)
      - [DC Surge Protection Device](#dc-surge-protection-device)
      - [Porcelain Fuse](#porcelain-fuse)
    - [2.1.7 MC4 Connectors](#217-mc4-connectors)
      - [MC4 Solar Panel Connectors](#mc4-solar-panel-connectors)
      - [4 in 1 T4 Connector](#4-in-1-t4-connector)
  - [2.2 **Mechanical Specifications**](#22-mechanical-specifications)
    - [2.2.1 Solar Panel Mounts](#221-solar-panel-mounts)
    - [2.2.2 Prefabricated portable Biogas Plant](#222-prefabricated-portable-biogas-plant)
  - [2.3 **Documentation Statistics** [2]](#23-documentation-statistics-2)
  - [2.4 **Document Readability indices** [3]](#24-document-readability-indices-3)
  - [2.5 **References**](#25-references)

---


## 2.1 **Electrical Specifications**
### 2.1.1 Battery
#### Luminous Red Charge RC 18000 150 Ah battery

<img src="https://m.media-amazon.com/images/I/61gCRXU1iMS._SL1500_.jpg" alt="connecting wires" width="250" height="250"/>

- For heavy-duty application with excellent overcharge tolerance, superior performance during long frequent power cuts, and minimum maintenance
-  fast battery charging with adaptive battery charging control technology

| Specifications                  | Value                                                       |
|---------------------------------|-------------------------------------------------------------|
| Brand                           | Luminous                                                    |
| Nominal Voltage                 | 12V                                                         |
| Rated Capacity(at room temp.)   | 150 ah (at room temp.)                                                     |
| Protections                     | Dust & water proof with heavy plastic body                  |
| Charging Current(Boost mode)    | 15.10A(starting), 7.60A(finishing)                           |
| Charging Current (Trickle mode) | 504 mA(max), 126 mA(min)                                    |
| Weight                          | 53.30 Kg (28.5 Kg dry weight) (+/- 5%)                                 |
| Dimensions                      | 50.2 $\times$ 44 $\times$ 19.1 cm (L $\times$ W $\times$ H) |
| Electrolyte Volume              | 20L (+/-5%)                                                      |
| Water Level Indicators          | 6                                                           |
| Cost                            | Rs. 12150 $\times$ 3 = Rs. 36450                           |

---

### 2.1.2 Backup Generator

The generator size should be of 1kW. In our system, generator will mostly be needed during winter when there is a lack of solar energy production. Since this is a backup system the below power consumed is assumed to be calculated under minimal load when running backup generator.

Total Instantaneous Power Consumed = 0.020*2(light)+0.5(misc) = 0.58kW

**Note**: Here the misc includes PC,stove and other appliances that we might/might not use under emergency situation. The generator should be able to run under the above conditions for 9hr(which is minimum requirement for overnight functionality). Spare fuel should always be kept in case of emergencies. 


| Specification      | Value                         |
| ------------------ | ----------------------------- |
| Manufacturer       | Generic                       |
| Fuel               | Petrol                        |
| Consumption        | 1L/hr under full load         |
| Capacity           | 10L                           |
| Rated voltage      | 220V+-15                      |
| Peak output power  | 1kVA                          |
| Weight             | 30kg                          |
| Cost               | Rs. 22,900                    |
| Size               | 1kW                           |

[Product Link](https://www.indiamart.com/proddetail/1-kva-portable-petrol-generator-23901047630.html)

---

### 2.1.3 Hybrid Solar Inverter (Built in Solar Charge Controller)
### 3KVA/ 36 V off Grid Solar Inverter

<img src="https://cdn.shopify.com/s/files/1/0270/1757/6533/products/1_4_1280x.jpg?v=1635314512" width = "400",height="500"/>

Luminous Solar Hybrid Inverter 3kVA/36 is an off grid hybrid solar inverter which allows smart management of Solar Power, Grid Supply and Battery to deliever uninterrupted power for all electrical appliances. It comes built in with an mppt technology based Solar Charge Controller that converts solar energy into electricity and stores power. 
-   3 kva system with 3500 watt solar panel support
-   super efficient as low conversion loss from battery
-   LCD Battery Monitoring system with display parameters such as Input Power, Output power load, battery health, battery percentage, Overload, MCB Trip and Over Temperature Protection
-   Surge warnings, safety alarms and troubleshooting Fault Codes 
-   BIS certified solar inverter and IP-21 protection level.
-  MCB protection in the case of any short circuit
-  Comprehensive protection against short-circuit, reverse polarity, battery overload etc.

| Specification                 | Value                             |
| ----------------------------- | --------------------------------- |
| Brand                         | Luminous                          |
| Rated Power                   | 3kVA                              |
| Waveform                      | Pure sine wave                    |
| Output Voltage Regulation     | 230VAC $\pm$ 2%                       |
| Output Frequency              | 50 Hz                             |
| Battery Bank Voltage          | 36 V(3x12V batteries)             |
| Input Voltage Mains Mode      | 180-260 VAC                       |
| Output Voltage Distortion(THD)| <=3%                              |
|Nominal Output Current from UPS| 11 A                              |
| Operating Temperature         | 0 - 45<sup>.</sup>C                          |
| Input Protection              | 32A MCB                           |
| Battery Charging Current      | 14A, 17A, 21A                     |
| Max. Relative Humidity @25<sup>.</sup>C  | upto 95%                          |
| Dimensions                    | D x W x H (mm) 300 x 417 x 452    |
| Net Weight                    | 32.5 kg                           |
| Cost                          | Rs. 39,950                        |



### Solar Charge Controller

Charge controllers are used to control the amount of current fed into the battery by the solar panels. This ensures the batteries are not overcharged during the day and don't leak current back to the panels during the night. So, Solar Charge Controller must be compatible with solar panel and the battery bank. Our Hybrid inverter comes built in with an MPPT Charge controller which is more efficient at DC Conversion compared to older PWM technology.

#### Sizing
Sizing of a controller depends on three factors
- Solar panel array’s maximum open-circuit voltage (Voc)
- Total Power rating of Solar panel array
- Battery Bank Voltage


Specifications of the in-built charge controller

| Specification                    | Value       |
| ------------------------------   | ----------- |
| Brand                            | Luminous    |
| Type                             | MPPT        |
| Nominal Battery Charging Current | 91A$\pm$ 2A     |
| Maximum Battery Charging Current | <=100A$\pm$ 10A |
| Maximum PV Array Power           | 3.5 kW      |
| Maximum PV Input Current(Imp)    | 38A         |
| Solar Input Voltage VMP          | 60V - 120V  |
| Solar Input Voltage VOC          | 75V - 150V  |

[Product Link](https://www.urbanurja.com/products/luminous-solarverter-pro-pcu-3-kva-36v-mppt-solar-inverter#)

---

### 2.1.4 High Efficiency Solar Panels

Solar panels collect clean renewable energy in the form of sunlight and convert that light into electricity which can then be used to provide power for electrical loads. 

The panels which we're using, are based on [mono PERC cells](https://regenpower.com/news/why-choose-mono-perc-panels-rooftop-solar/), which results into higher electricity generation due to higher light absorption per unit area, when compared to traditional panels.
 
It also paves the way for more power output per panel, which means less number of panels are required for a given power requirement. It means less expenditure for 
[panel mounts](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSWhB7u8DxJiUJTM2uH5U-6Ml3h3SoByqJd8g&usqp=CAU).

<img src = 
"https://cdn.shopify.com/s/files/1/2980/5140/products/dimension_fcef7a49-c267-4a58-b571-90de3319af24_1000x.jpg?v=1618825077" height=500>

We'll be using 8 such panels in our system.

| Specification (Single panel) | Value         |
| ---------------------------- | ------------- |
| Cost                         | &#8377;20,000 |
| Operating Voltage            | 24V           |
| Dimensions                   | 6.9ft X 3.4ft |
| Manufacturer                 | Loom Solar    |
| Rated Output Power (Peak)    | 440W          |
| Output Voltage at max. power | 42V           |
| Output Current at max. power | 10.5A         |


*Above electrical data is for, Irradiance: 1000W/m² and Cell Temperature:25°C*

[Product Link](https://www.loomsolar.com/products/loom-solar-panel-shark-super-high-efficiency-module)

---

### 2.1.5 Wires
#### Solar DC Cable
DC Solar Panel cables are required to connect the array of solar panels in series with each other and then carry the output DC Current to the Solar Charge Controller.

When choosing DC Solar Panel wires, some things should be kept in mind
- The wires should be of sufficient diameter to ensure that no overheating occurs
- The wires should be of adequate current rating
- UV resistance to ensure longevity

<img src="https://m.media-amazon.com/images/I/417e-1jmi4S.jpg">



| Specification             | Value                 |
| ------------------------- | --------------------- |
| Brand                     | Microtek              |
| Current carrying capacity | 80 A                  |
| Cross Sectional Area      | 10 mm²                |
| Length                    | 15m Red and 15m Black |
| Cost                      | &#8377;1990           |

[Product Link](https://www.amazon.in/Microtek-Solar-Cable-Protected-15Meter/dp/B08BBYX28X/)

####  Household connection wires
Connecting wires would be used to connect different appliances in the energy grid.  Hence they should be able to carry high current and be well insulated.

<img src="https://rukminim1.flixcart.com/image/416/416/k5zn9u80/electrical-wire/h/e/b/whffdnka1x50-fr-sc-5-mm-wire-black-90mtr-havells-original-imafa8rhtuurspyd.jpeg?q=70" alt="connecting wires" height="300"/>



| Specification             | Value                     |
| ------------------------- | ------------------------- |
| Brand                     | Havells                   |
| Length                    | 90 m                      |
| Cross-sectional area      | 2.5 sq mm                 |
| Current carrying capacity | 28 A                      |
| Voltage Grade             | 1100 V                    |
| Insulation material       | HRFR PV                   |
| Conductor material        | ETP Grade Annealed Copper |
| Cost                      | &#8377;2,871              |

[Product Link](http://dl.flipkart.com/dl/havells-hrfr-pvc-2-5-sq-mm-black-90-m-wire/p/itmbcd2c1b016975?pid=ELWFHWS4S7YZAAQ7&cmpid=product.share.pp)


---
### 2.1.6 Safety Measures

 ####  AC Circuit Breaker
 
 A separate AC Breaker between the AC Input and Inverter is required to ensure tha the inverter can be securely disconnected during maintenance and secured from AC Input over current

 <img src = "https://m.media-amazon.com/images/I/71FN9t0iyQL._SL1500_.jpg" width = 300>


| Specification  | Value                |
| -------------- | -------------------- |
| Brand          | Siemens              |
| Current Rating | 63 A                 |
| No. of Poles   | 4                    |
| Dimensions     | 7.1 cm X 7 cm X 9 cm |
| Weight         | 660 g                |
| Material       | Polycarbonate        |
| Color          | White                |
| Cost           | &#8377;   1500       |
 
 [Product Link](https://www.amazon.in/Siemens-Pole-White-1-Piece-5SL64637RC/dp/B01D4QL6RC)

#### DC Circuit Breaker

A DC Circuit breaker between the Solar Panels and Inverter is required for disconnecting the solar panels safely for maintenance or replacement. The Circuit breaker also protects the inverter from over current damage

<img src = "https://m.media-amazon.com/images/I/71JEQ-sPGaL._SL1500_.jpg" width = 200>

| Specification        | Value                  |
| -------------------- | ---------------------- |
| Brand                | FEEO                   |
| Circuit Breaker Type | Standard               |
| Current Rating       | 63 A                   |
| No. of Poles         | 2                      |
| Voltage              | 800 V (DC)             |
| Dimensions           | 7.1 cm X 3.6 cm X 8 cm |
| Cost                 | &#8377;999             |

[Product Link](https://www.amazon.in/FEEO-63A-Double-Pole-MCB/dp/B01LF8E0T2/ref=sr_1_3?crid=2B9MK4LCK4WR2&keywords=feeo&qid=1642516418&sprefix=dc+circuit+breaker%2Caps%2C864&sr=8-3)

#### DC Surge Protection Device

The DC Surge Protector protects the inverter and panels from any unforeseen voltage surges in instances such as Lightning strikes

<img src = "https://m.media-amazon.com/images/I/61l8Y7CfuAL._SL1500_.jpg" width = 200>

| Specification      | Value                |
| ------------------ | -------------------- |
| Brand              | Kenbrook Solar       |
| Overvoltage Rating | 600V                 |
| No. of Poles       | 2                    |
| Dimension          | 9 cm X 6 cm X 3.5 cm |
| Weight             | 245 g                |
| Cost               | &#8377;799           |

[Product Link](https://www.amazon.in/Kenbrook-Solar-Elmak-Protection-Device/dp/B09NTQDJGP/ref=sr_1_2?crid=108RSYE3E2S5V&keywords=solar%2Bsurge%2Bprotection&qid=1642516582&sprefix=solar%2Bsurge%2Bprotectio%2Caps%2C767&sr=8-2&th=1)

####   Porcelain Fuse
<img src = "https://m.media-amazon.com/images/I/71b9tS1f2bL._SL1500_.jpg" width = 300>

| Specification      | Value               |
| ------------------ | ------------------- |
| Brand              | Anchor              |
| AC Adapter Current | 32 A                |
| Voltage            | 415 V               |
| Material           | Ceramic             |
| Dimensions         | 10 cm X 5 cm X 5 cm |
| Cost               | &#8377;185          |

[Product Link](https://www.amazon.in/Anchor-9311-Porcelain-Pilot-Ivory/dp/B00V4VJ7IK/ref=sr_1_12?crid=NPAHCXCDE79L&keywords=fuses&qid=1642478482&sprefix=fuses%2Caps%2C376&sr=8-12)

---

### 2.1.7 MC4 Connectors
#### MC4 Solar Panel Connectors

MC4 Connectors are required for a safe and convenient connection between the solar panel arrays.   
The Kenbrook Solar MC4 Connectors are UV resistant, waterproof and anti-flame boasting an estimated life of upto 25 years and thus require minimum maintenance.

<img src="https://m.media-amazon.com/images/I/81DukcckFRL._SL1500_.jpg" height="300">

| Specification | Value                                            |
| ------------- | ------------------------------------------------ |
| Brand         | Kenbrook                                         |
| Material      | Copper (Tin Plated) \| PPO + PA (Outer Covering) |
| Dimensions    | 6 x 4 x 2 cm                                     |
| Quantity      | 10 Male + Female MC4 Connectors                  |
| Cost          | &#8377;449                                       |

[Product Link](https://www.amazon.in/Kenbrook-Solar-Connector-Panel-Connection/dp/B08VNW7DLP/)

#### 4 in 1 T4 Connector

T4 Connector is required to connect the 2x4 parallel solar panel array to the solar charge controller. The T4 connector also comes with UV Resistance, anti flame and water resistance

<img src="https://m.media-amazon.com/images/I/81v6jkEqD4L._SL1500_.jpg" height="300">

| Specification | Value                                            |
| ------------- | ------------------------------------------------ |
| Brand         | Kenbrook                                         |
| Material      | Copper (Tin Plated) \| PPO + PA (Outer Covering) |
| Dimension     | 17 x 17 x 2 cm                                   |
| Quantity      | 2 sets                                           |
| Cost          | &#8377;799                                       |

[Product Link](https://www.amazon.in/Kenbrook-Solar-T4-Connector-Support/dp/)

---

## 2.2 **Mechanical Specifications**
### 2.2.1 Solar Panel Mounts

Panel mounts are used to fix solar panels on surfaces like roofs, building facades, or ground. The panel array is mounted with each panel aligned at an angle. This angle is variable and mounts should be bought according to the type of rooftop. We'll be using ones with 25° inclination.

<img src = 
"https://cdn.shopify.com/s/files/1/2980/5140/products/LoomSolar2rowDesign4PanelStand375watt_2_700x.jpg?v=1624973202" height=500>

We'll be using 2 such mounts for our system, which consists of 8 panels.

| Specification  (Single unit) | Value           |
| ---------------------------- | --------------- |
| Cost                         | &#8377;12,000   |
| Inclination                  | 25°             |
| Dimensions(Leg)              | 150cm X 60cm    |
| Manufacturer                 | Loom Solar      |
| Weight                       | 50kg            |
| Material                     | Galvanised Iron |
| Holding Capacity             | 4 Panels        |

[Product Link](https://www.loomsolar.com/collections/solar-panel-stand/products/loom-solar-2-row-design-4-panel-stand-375-watt)

---

### 2.2.2 Prefabricated portable Biogas Plant

With a biogas plant, organic waste and side streams are converted into income by producing renewable energy and organic fertilizer cost-effectively. Produced biogas can be utilized for electricity and heat production. Biogas can be also upgraded to biomethane that can be used as vehicle fuel or fed into the natural gas grid as a substitute for fossil gas.

<img src = "https://5.imimg.com/data5/JI/DI/YS/SELLER-28929530/biogas-plant-500x500.jpeg">


| Specification      | Value                     |
| ------------------ | ------------------------- |
| Cost               | &#8377;23,599             |
| Plant Capacity     | 2 m³                      |
| Area to be covered | 3m X 3m                   |
| Company            | Gujarat Renewable Energia |
| Body Material      | PVC Coated Fabric         |
| Shape              | Round                     |
| Color              | Gray                      |

[Product Link](https://www.indiamart.com/proddetail/flexible-biogas-plant-21839483148.html)

---

## 2.3 **Documentation Statistics** [2]

-   **Word count**: 2637
-   **Total number of unique words**: 922
-   **Total number of repeated words**: 1715
-   **Total number of sentences**: 49
-   **Total number of characters**: 22879
-   **Total number of characters without spaces**: 16198
-   **Total number of syllables**: 4471
-   **Average number of words per sentence**: 54
-   **Average number of characters per sentence**: 467
-   **Average number of characters per word**: 6.1
-   **Average number of syllables per word**: 1.69

The above results were obtained using https://wordcounter.net/.

## 2.4 **Document Readability indices** [3]

-   **Flesch Reading Ease score**: 58
-   **Dale-Chall Readability score**: 8.3
-   **Flesch-Kincaid Grade level**: 8
-   **The Coleman-Liau Index**: 16
-   **Automated Readability Index**: 12
-   **SMOG Formula score**: 12
-   **Spache Readability score**: 4

The above scores were obtained using Visual Studio Code extension called Readability Check by jemcclin.




## 2.5 **References**

[1] [GitHub - Off Grid Energy Design - Tribe E](https://github.com/CrypticPoet/off-grid-energy-design)

[2] [WordCounter - Count Words & Correct Writing](https://wordcounter.net/)

[3] [Readability Check - Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=jemcclin.readabilitycheck)
