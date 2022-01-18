<font size="5"> <center> ELP305 Design and Systems Laboratory </center> </font>
<font size="4"> <center> Semester 2, 2021-2022 </center></font>
<font size="3"> <center> Tribe E </center></font>

# 2. **SUNERGY Specifications**

In the following document, we give a brief on various specifications of the components that we will be using in our off-grid living solution. We also mention their properties and why we have chosen them along with the best quotation available for each component.
**NOTE:** These specifications may change as the design work progresses further.

---

<font size="4">**Table of Contents:**</font>
- [2. **SUNERGY Specifications**](#2-sunergy-specs)
  - [2.1 **Electrical Specifications**](#21-elec-specs)
  - [2.2 **Mechanical Specifications**](#22-mech-specs)
  - [2.4 **References**](#24-references)
  - [2.5 **Documentation Statistics**](#25-documentation-statistics)
  - [2.6 **Document Readability indices**](#26-document-readability-indices)

---

## 2.1 **Electrical Specifications**
### 2.1.1 Battery
#### Luminous Red Charge RC 25000 200 Ah battery

- For heavy-duty application with excellent overcharge tolerance, superior performance during long frequent power cuts, and minimum maintenance
-  Fast battery charging with adaptive battery charging control technology to prevent overcharging

We select a battery bank such that we can ensure ample power for upto 24 hours. For this, a suitable choice is 4 batteries of 12V, 200 Ah rating connected in series. 

<img src="https://m.media-amazon.com/images/I/61q4Rl4ZmOS._SL1500_.jpg" alt="connecting wires" height="300"/>


| Specifications                  | Value                                                       |
| ------------------------------- | ----------------------------------------------------------- |
| Brand                           | Luminous                                                    |
| Nominal Voltage                 | 12V                                                         |
| Rated Capacity(at room temp.)   | 200 ah                                                      |
| Protections                     | Dust & water proof with heavy plastic body                  |
| Charging Current(Boost mode)    | 20.2A(starting), 10.1A(finishing)                           |
| Charging Current (Trickle mode) | 672 mA(max), 168 mA(min)                                    |
| Weight                          | 60 Kg (34.4 Kg dry weight)                                  |
| Dimensions                      | 50.2 <img src="https://render.githubusercontent.com/render/math?math=\times"> 44 <img src="https://render.githubusercontent.com/render/math?math=\times"> 19.1 cm (L <img src="https://render.githubusercontent.com/render/math?math=\times"> W <img src="https://render.githubusercontent.com/render/math?math=\times"> H) |
| Electrolyte Volume              | 19.9L                                                       |
| Water Level Indicators          | 6                                                           |
| Cost                            | &#8377; 14,780 <img src="https://render.githubusercontent.com/render/math?math=\times"> 4 = &#8377; 59120                           |

[Product Link](https://www.amazon.in/dp/B07BCDDXZJ/ref=cm_sw_r_apan_glt_i_J1N15MKV18TN69RT1Q67?_encoding=UTF8&psc=1)

---

### 2.1.2 Backup Generator

The generator size should be of 3kW. In our system, generator will mostly be needed during winter when there is a lack of solar energy production. So the power calculation will be done under winter conditions. And since this is a backup system the below power consumed is assumed to be calculated under maximum load when running backup generator.

Total Instantaneous Power Consumed = 0.036*4(light)+1.5(house heater)+0.15(fridge)+1(misc.) = 2.8kW

**Note**: Here the misc. includes TV,PC, and other appliances that we might/might not use under emergency situation. The generator should be able to run under the above conditions for 12hr. Spare fuel should always be kept in case of emergencies. 


| Specification      | Value                         |
| ------------------ | ----------------------------- |
| Manufacturer       | Techno Machineries            |
| Fuel               | Kerosene(Run), Petrol (Start) |
| Consumption        | 1L/hr under full load         |
| Capacity           | 12L                           |
| Rated voltage      | 220V+-15                      |
| Rated output power | 2.8kW                         |
| Peak output power  | 3kW                           |
| Weight             | 40kg                          |
| Dimensions         | 630x500x600mm                 |
| Cost               | &#8377; 32,900                    |

[Product Link](https://www.indiamart.com/proddetail/portable-generators-3kw-22423030173.html)

---

### 2.1.3 Hybrid Solar Inverter (Built in Solar Charge Controller)
#### 5KVA/ 48 V off Grid Solar Inverter


<img src="https://m.media-amazon.com/images/I/81H1wHEtr3L._SL1500_.jpg" height="300"/>

FlinFuzion Solar Hybrid Inverter 5kVA/48V is an off grid hybrid solar inverter which supports lead acid and lithium batteries both. It comes built in with an mppt technology based Solar Charge Controller that converts solar energy into electricity and stores power.   

-   Off grid hybrid solar inverter with lithium battery / Lead acid battery support functionality.
-   5 kva system with 5000 watt solar panel support
-   super efficient as low conversion loss from battery
-   LCD Battery Monitoring system with display parameters such as Input Power, Output power load, battery health, battery percentage
-   Surge warnings, safety alarms and troubleshooting Fault Codes 
-   Included battery monitoring software with USB and RS232 Data Ports

| Specification                 | Value                             |
| ----------------------------- | --------------------------------- |
| Brand                         | Flin Energy                       |
| Rated Power                   | 5kVA                              |
| Waveform                      | Pure sine wave                    |
| Output Voltage Regulation     | 230VAC <img src="https://render.githubusercontent.com/render/math?math=\pm"> 5%                   |
| Output Frequency              | 50 Hz                             |
| Battery Voltage               | 48 VDC                            |
| Battery Overcharge protection | 63 VDC                            |
| Battery Equalization          | Yes                               |
| Maximum AC Charge Current     | 60 A                              |
| Peak Efficiency               | 93%                               |
| Overload Protection           | 5s@≥150% load; 10s@110%~150% load |
| Surge Capacity                | 10kVA for 5 seconds               |
| No Load Power Consumption     | <35W                              |
| Dimensions                    | D x W x H (mm) 100 x 300 x 440    |
| Net Weight                    | 10 kg                             |
| Cost                          | &#8377; 78,800                        |


#### Solar Charge Controller

Charge controllers are used to control the amount of current fed into the battery by the solar panels. This ensures the batteries are not overcharged during the day and don't leak current back to the panels during the night. So, Solar Charge Controller must be compatible with solar panel and the battery bank. Our Hybrid inverter comes built in with an MPPT Charge controller which is more efficient at DC Conversion compared to older PWM technology.

##### Sizing
Sizing of a controller depends on three factors
- Solar panel array’s maximum open-circuit voltage (Voc)
- Total Power rating of Solar panel array
- Battery Bank Voltage

##### Required Ratings
- **Solar panel array’s maximum open-circuit voltage (Voc)**: The 8 solar panels are arranged in a 2x4 array, such that 4 pairs of solar panels are in parallel, with each pair in series. Each Solar panel has a open circuit voltage of 49V. So, the maximum open circuit voltage of solar panel is 49x2= 98V.

- **Total Power rating of Solar panel array**: Since, we are using 8 solar panels with 440 W power rating.Hence, the total power rating of Solar panel array is 3520W.

- **Battery Bank Voltage**: Battery Bank Volatge of our system is 48V.

Now, from power rating and battery bank voltage, we can calculate the required Ampere rating of the controller, which is equal to (power rating/Bank Voltage).
So, the required Ampere rating is 73.33A.
The required maximum input Voc of controller = maximum open circuit voltage of solar panel.

Hence, Our Controller must have atleast 98V input Voc rating and 73.33A current rating. We select the controller such that these two figures slightly exceed the requirements to build a safety margin.

Specifications of the in-built charge controller

| Specification                  | Value       |
| ------------------------------ | ----------- |
| Brand                          | Flin Energy |
| Type                           | MPPT        |
| Maximum Solar Charging Current | 80A         |
| Maximum PV Array Power         | 5 kW        |
| Operating Voltage Range        | 120-450V    |
| Nominal PV Voltage             | 240V        |
| Maximum PV VOC                 | 500V        |

[Product Link](https://www.amazon.in/Flin-Energy-FlinFuzion-Hybrid-Inverter/dp/B0793KN2K8/)

---

### 2.1.4 High Efficiency Solar Panels

Solar panels collect clean renewable energy in the form of sunlight and convert that light into electricity which can then be used to provide power for electrical loads. 

The panels which we're using, are based on [mono PERC cells](https://regenpower.com/news/why-choose-mono-perc-panels-rooftop-solar/), which results into higher electricity generation due to higher light absorption per unit area, when compared to traditional panels.
 
It also paves the way for more power output per panel, which means less number of panels are required for a given power requirement. It means less expenditure for 
[panel mounts](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSWhB7u8DxJiUJTM2uH5U-6Ml3h3SoByqJd8g&usqp=CAU).

<img src = 
"https://cdn.shopify.com/s/files/1/2980/5140/products/dimension_fcef7a49-c267-4a58-b571-90de3319af24_1000x.jpg?v=1618825077">

We'll be using 8 such panels in our system.

| Specification (Single panel) | Value                |
| ---------------------------- | -------------------- |
| Cost                         | &#8377; 20,000        |
| Operating Voltage            | 24V                  |
| Dimensions                   | 6.9ft <img src="https://render.githubusercontent.com/render/math?math=\times"> 3.4ft |
| Manufacturer                 | Loom Solar           |
| Rated Output Power (Peak)    | 440W                 |
| Output Voltage at max. power | 42V                  |
| Output Current at max. power | 10.5A                |


*Above electrical data is for, Irradiance: 1000W/<img src="https://render.githubusercontent.com/render/math?math=m^{2}"> and Cell Temperature:25&#8451*
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



| Specification             | Value                     |
| ------------------------- | ------------------------- |
| Brand                     | Microtek                  |
| Current carrying capacity | 80 A                      |
| Cross Sectional Area      | 10 <img src="https://render.githubusercontent.com/render/math?math=mm^{2}">                |
| Length                    | 15 m Red and 15 m Black |
| Cost                      | &#8377; 1990                  |

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
| Cost                      | &#8377; 2,871                 |

[Product Link](http://dl.flipkart.com/dl/havells-hrfr-pvc-2-5-sq-mm-black-90-m-wire/p/itmbcd2c1b016975?pid=ELWFHWS4S7YZAAQ7&cmpid=product.share.pp)


---
### 2.1.6 Safety Measures

 ####  AC Circuit Breaker
 
 A separate AC Breaker between the AC Input and Inverter is required to ensure tha the inverter can be securely disconnected during maintenance and secured from AC Input over current

 <img src = "https://m.media-amazon.com/images/I/71FN9t0iyQL._SL1500_.jpg" width = 300>


| Specification  | Value                              |
| -------------- | ---------------------------------- |
| Brand          | Siemens                            |
| Current Rating | 63 A                               |
| No. of Poles   | 4                                  |
| Dimensions     | 7.1 cm <img src="https://render.githubusercontent.com/render/math?math=\times"> 7 cm <img src="https://render.githubusercontent.com/render/math?math=\times"> 9 cm |
| Weight         | 660 g                              |
| Material       | Polycarbonate                      |
| Color          | White                              |
| Cost           | &#8377;    1500                     |
 
 [Product Link](https://www.amazon.in/Siemens-Pole-White-1-Piece-5SL64637RC/dp/B01D4QL6RC)

#### DC Circuit Breaker

A DC Circuit breaker between the Solar Panels and Inverter is required for disconnecting the solar panels safely for maintenance or replacement. The Circuit breaker also protects the inverter from over current damage

<img src = "https://m.media-amazon.com/images/I/71JEQ-sPGaL._SL1500_.jpg" width = 200>

| Specification        | Value                                |
| -------------------- | ------------------------------------ |
| Brand                | FEEO                                 |
| Circuit Breaker Type | Standard                             |
| Current Rating       | 63 A                                 |
| No. of Poles         | 2                                    |
| Voltage              | 800 V (DC)                           |
| Dimensions           | 7.1 cm <img src="https://render.githubusercontent.com/render/math?math=\times"> 3.6 cm <img src="https://render.githubusercontent.com/render/math?math=\times"> 8 cm |
| Cost                 | &#8377; 999                           |

[Product Link](https://www.amazon.in/FEEO-63A-Double-Pole-MCB/dp/B01LF8E0T2/ref=sr_1_3?crid=2B9MK4LCK4WR2&keywords=feeo&qid=1642516418&sprefix=dc+circuit+breaker%2Caps%2C864&sr=8-3)

#### DC Surge Protection Device

The DC Surge Protector protects the inverter and panels from any unforeseen voltage surges in instances such as Lightning strikes

<img src = "https://m.media-amazon.com/images/I/61l8Y7CfuAL._SL1500_.jpg" width = 200>

| Specification      | Value                              |
| ------------------ | ---------------------------------- |
| Brand              | Kenbrook Solar                     |
| Overvoltage Rating | 600V                               |
| No. of Poles       | 2                                  |
| Dimension          | 9 cm <img src="https://render.githubusercontent.com/render/math?math=\times"> 6 cm <img src="https://render.githubusercontent.com/render/math?math=\times"> 3.5 cm |
| Weight             | 245 g                              |
| Cost               | &#8377; 799                         |

[Product Link](https://www.amazon.in/Kenbrook-Solar-Elmak-Protection-Device/dp/B09NTQDJGP/ref=sr_1_2?crid=108RSYE3E2S5V&keywords=solar%2Bsurge%2Bprotection&qid=1642516582&sprefix=solar%2Bsurge%2Bprotectio%2Caps%2C767&sr=8-2&th=1)

####   Porcelain Fuse
<img src = "https://m.media-amazon.com/images/I/71b9tS1f2bL._SL1500_.jpg" width = 300>

| Specification      | Value                             |
| ------------------ | --------------------------------- |
| Brand              | Anchor                            |
| AC Adapter Current | 32 A                              |
| Voltage            | 415 V                             |
| Material           | Ceramic                           |
| Dimensions         | 10 cm <img src="https://render.githubusercontent.com/render/math?math=\times"> 5 cm <img src="https://render.githubusercontent.com/render/math?math=\times"> 5 cm |
| Cost               | &#8377; 185                        |

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
| Dimensions    | 6 x 4 x 2 cm                                   |
| Quantity      | 10 Male + Female MC4 Connectors                  |
| Cost          | &#8377; 449                                          |

[Product Link](https://www.amazon.in/Kenbrook-Solar-Connector-Panel-Connection/dp/B08VNW7DLP/)

#### 4 in 1 T4 Connector

T4 Connector is required to connect the 2x4 parallel solar panel array to the solar charge controller. The T4 connector also comes with UV Resistance, anti flame and water resistance

<img src="https://m.media-amazon.com/images/I/81v6jkEqD4L._SL1500_.jpg" height="300">

| Specification | Value                                            |
| ------------- | ------------------------------------------------ |
| Brand         | Kenbrook                                         |
| Material      | Copper (Tin Plated) \| PPO + PA (Outer Covering) |
| Dimension     | 17 x 17 x 2 cm                                 |
| Quantity      | 2 sets                                           |
| Cost          | &#8377; 799                                          |

[Product Link](https://www.amazon.in/Kenbrook-Solar-T4-Connector-Support/dp/)

---

## 2.2 **Mechanical Specifications**
### 2.2.1 Solar Panel Mounts

Panel mounts are used to fix solar panels on surfaces like roofs, building facades, or ground. The panel array is mounted with each panel aligned at an angle. This angle is variable and mounts should be bought according to the type of rooftop. We'll be using ones with 25° inclination.

<img src = 
"https://cdn.shopify.com/s/files/1/2980/5140/products/LoomSolar2rowDesign4PanelStand375watt_2_700x.jpg?v=1624973202">

We'll be using 2 such mounts for our system, which consists of 8 panels.

| Specification  (Single unit)  |  Value                |
| ---                           |        ---            |
| Cost                          | &#8377; 12,000         |
| Inclination                   | 25°                   |
| Dimensions(Leg)               | 150cm <img src="https://render.githubusercontent.com/render/math?math=\times"> 60cm   |
| Manufacturer                  | Loom Solar            |
| Weight                        | 50kg                  |
| Material                      | Galvanised Iron       |
| Holding Capacity              | 4 Panels              |
[Product Link](https://www.loomsolar.com/collections/solar-panel-stand/products/loom-solar-2-row-design-4-panel-stand-375-watt)

---

### 2.2.2 Prefabricated portable Biogas Plant

With a biogas plant, organic waste and side streams are converted into income by producing renewable energy and organic fertilizer cost-effectively. Produced biogas can be utilized for electricity and heat production. Biogas can be also upgraded to biomethane that can be used as vehicle fuel or fed into the natural gas grid as a substitute for fossil gas.

<img src = "https://5.imimg.com/data5/JI/DI/YS/SELLER-28929530/biogas-plant-500x500.jpeg">


| Specification      | Value                     |
| ------------------ | ------------------------- |
| Cost               | &#8377; 23,599                |
| Plant Capacity     | 2 <img src="https://render.githubusercontent.com/render/math?math=m^{3}">                 |
| Area to be covered | 3m <img src="https://render.githubusercontent.com/render/math?math=\times"> 3m            |
| Company            | Gujarat Renewable Energia |
| Body Material      | PVC Coated Fabric         |
| Shape              | Round                     |
| Color              | Gray                      |

[Product Link](https://www.indiamart.com/proddetail/flexible-biogas-plant-21839483148.html)

---









