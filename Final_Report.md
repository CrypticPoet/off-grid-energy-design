# ELP305 Design and Systems Laboratory
## Semester 2, 2021-2022 
### Tribe E


# SUNERGY: Final Report

**NOTE** The GitHub repository that our tribe is using is linked [here](https://github.com/CrypticPoet/off-grid-energy-design)

## Table of Contents

- [**SUNERGY: Final Report**](#sunergy-final-report)
  - [**Authors**](#authors)
  - [**Documentation Statistics**](#documentation-statistics)
    - [**Text Statistics**](#text-statistics)
    - [**Readability Indices**](#readability-indices)
  - [**Preamble**](#preamble)
    - [**List of Abbreviations**](#list-of-abbreviations)
    - [**List of Tables**](#list-of-tables)
    - [**List of Figures**](#list-of-figures)
  - [**Project Management**](#project-management)
  - [**Abstract**](#abstract)
  - [**Aim**](#aim)
  - [**Scope**](#scope)
  - [**Requirements**](#requirements)
    - [**Base Setup**](#base-setup)
    - [**Basic Requirements**](#basic-requirements)
    - [**Technical Requirements**](#technical-requirements)
  - [**Specifications**](#specifications)
    - [**Electrical Specifications**](#electrical-specifications)
    - [**Mechanical Specifications**](#mechanical-specifications)
  - [**Design**](#design)
    - [**CAD/Assembly**](#cadassembly)
    - [**Wiring Diagram**](#wiring-diagram)
  - [**Cost Analysis**](#cost-analysis)
  - [**Reuse of Materials**](#reuse-of-materials)
  - [**Attributions**](#attributions)
  - [**References**](#references)

---

## Authors
| S. No. | Name | Email id | Role | Performance |
|------:|:----:|:--------:|:----:|:----------:|
Table 1
---

## Documentation Statistics
#### Text Statistics
<!-- To be changed -->

| Word Count | # unique words | # repeated words | # sentences | # characters | # characters w/o spaces | # syllables |
|------------|----------------|------------------|-------------|--------------|-------------------------|-------------|
| 434        | 922            | 1715             | 11          | 3592         | 3204                    | 941         |

| Avg # words per sentence | Avg # characters per sentence | Avg # characters per word | Avg # syllables per word |
|--------------------------|-------------------------------|---------------------------|--------------------------|
| 40                       | 327                           | 7.4                       | 2.16                     |

Table 2 :The above results were obtained using https://wordcounter.net/.

#### Readability indices
<!-- To be changed -->

| Readability Index                | Score |
|----------------------------------|-------|
| Flesch Reading Ease score        | 61    |
| Dale-Chall Readability score     | 8.8   |
| Flesch-Kincaid Grade level       | 7     |
| The Coleman-Liau Index           | 14    |
| Automated Readability Index      | 11    |
| SMOG Formula score               | 12    |
| Spache Readability score         | 4     |

Table 3 :The above scores were obtained using Visual Studio Code extension called Readability Check by jemcclin.

---

## Preamble

#### List of Abbreviations
|  S. No.  | Abbreviation|Stands For|
 | :---:|:-----:|:--------------------:|
 |1.| AC | Alternating Current|
 |2.| BIS | Bureau of Indian Standards|
|3.| CAD |Computer Aided Design|
|4.| DC| Direct Current|
|5.| ETP | Electrolytic Tough Pitch |
|6.| HRFR|Heat Resistant Flame Retardant|
|7.| IMP| Current at Maximum Power|
|8.| IP | Ingress Protection|
|9.| LED| Light Emitting Diode|
|10.| MPPT | Maximum Power Point Tracking|
|11.| misc| Miscellaneous|
|12.| MCB| Miniature Circuit Breaker|
|13.| MC4 Connector|Multi-Contact 4 mm diameter contact pin Connector|
|14.| PERC| Passivated Emitter and Rear Contact|
|15.| PWM| Pulse Width Modulation|
|16.| PC | Personal Computer |
|17.| PA| Polyamide|
|18.| PPO| Polyphenylene Oxide |
|19.| UV | UltraViolet|
|20.| VMP| Voltage at Maximum Power|
|21.| Voc| Voltage at Open Circuit|

#### List of Tables

|  S. No.  | Table|
| :---:|:-----:|
| 1.|  [**Authors**](#authors)|
|2.| [**Text Statistics**](#text-statistics)|
|3.|[**Readability indices**](#readability-indices)|
|4.|[**Power Requirements**](#basic-requirements)|
|5.|[**Battery**](#battery)|
|6.|[**Backup Generator**](#backup-generator)|
|7.|[**Hybrid Solar Inverter**](#hybrid-solar-inverter-built-in-solar-charge-controller)|
|8.|[**Solar Charge Controller**](#solar-charge-controller)|
|9.|[**High Efficiency Solar Panels**](#high-efficiency-solar-panels)|
|10.|[**Solar DC Cable**](#solar-dc-cable)|
|11.|[**Household connection wires**](#household-connection-wires)|
|12.|[**AC Circuit Breakers**](#ac-circuit-breaker)|
|13.|[**DC Circuit Breakers**](#dc-circuit-breaker)|
|14.|[**DC Surge Protection Device**](#dc-surge-protection-device)|
|15.|[**Porcelain Fuse**](#porcelain-fuse)|
|16.|[**MC4 Solar Panel Connectors**](#mc4-solar-panel-connectors)|
|17.|[**4 in 1 T4 Connector**](#4-in-1-t4-connector)|
|18.|[**Solar Panel Mounts**](#solar-panel-mounts)|
|19.|[**Cost Analysis**](#cost-analysis)|

#### List of Figures

|  S. No.  | Figures|
 | :---:|:-----:|
 |1.| [**Mindmap for Requirements**](#requirements)|
 |2.|[**Mindmap for Specifications**](#specifications)|
 |3.|[**Luminous Red Charge RC 18000 150 Ah Battery**](#luminous-red-charge-rc-18000-150-ah-battery)|
|4.|[**Off Grid Solar Inverter**](#3kva-36-v-off-grid-solar-inverter)|
|5.|[**Solar Panels**](#high-efficiency-solar-panels)|
|6.|[**Solar DC Cables**](#solar-dc-cable)|
|7.|[**Household Connection Wires**](#household-connection-wires)|
|8.|[**AC Circuit Breaker**](#ac-circuit-breaker)|
|9.|[**DC Circuit Breaker**](#dc-circuit-breaker)|
|10.|[**DC Surge Protection Device**](#dc-surge-protection-device)|
|11.|[**Porcelain Fuse**](#porcelain-fuse)|
|12.|[**MC4 Solar Panel Connectors**](#mc4-solar-panel-connectors)|
|13.|[**4 in 1 T4 Connector**](#4-in-1-t4-connector)|
|14.|[**Solar Panel Mounts**](#solar-panel-mounts)|
|15.|[**Mindmap for Design**](#design)|
| 16. |[**Front View of Designed House**](#cadassembly)|
| 17. |[**Side View of Designed House**](#cadassembly)|
| 18. |[**Top View of Designed House**](#cadassembly) |
|19.  |[**Orthographic View of Designed House**](#cadassembly)|
|20.|[**Side View of Solar Panels**](#cadassembly)|
|21.|[**Front View of Solar Panels**](#cadassembly)|
|22.|[**Top View of Solar Panels**](#cadassembly)|
|23.|[**Side View of Inverter**](#cadassembly)|
|24.|[**Front View of Inverter**](#cadassembly)|
|25.|[**Top View of Inverter**](#cadassembly)|
|26.|[**Side View of Battery**](#cadassembly)|
|27.|[**Front View of Battery**](#cadassembly)|
|28.|[**Top View of Battery**](#cadassembly)|
|29.| [**Wiring Diagram**](#wiring)|

---

## Project Management

---

## Abstract
The necessity for increased power generation is unavoidable since the world's electricity consumption rises on a regular basis. As a result, we need renewable energy resources which can meet electrical power demand up to a large fraction of total demand. In this report we are designing a cost-effective self-sustainable electrical system using the available solution in the market to meet the general electrical requirements of an Indian Household. Solar energy is used as major renewable energy source as it is versatile compared to other renewable sources, easy and feasible to convert in electrical form.

---

## Aim

In this project we aim to design a cost-effective off-grid self sustainable electrical system using the available products in market. In our final report we revisit our previously submitted requirements and specifications and adjust them accordingly to match the final design cycle of the project.  Here we try to compile all the previous product cycles in order to deliver the final design of the electrical system alongside it's cost analysis and vendor information to ensure smooth installation.

---

## Scope

In this hustling daily routine, many people tend to resort to a house in the forest for peace of mind. Also, there is a large part of India where electricity has not reached yet. This is an off-grid solution for daily energy needs such as electricity and heat energy. 

We will be using solar panels for electricity along with a diesel/petrol generator for backup in order to meet the electricity needs. A biogas plant for heat energy needs will also be used as a backup.

We will be covering the technical aspects of the components involved such as the electrical specifications of all components needed for a fully functional solar power setup, power output of fuel generator. We will also cover the physical/mechanical specifications such as dimensions etc. Apart from this, it also includes supplier information, 3D Diagrams of setup/assembly and cost analysis such as price of components along with installation charges.

The solution has been made keeping in mind a specific geographical location (A forest in eastern coast of India) which has ample fuel wood, natural water sources nearby, sufficient amount of biomass (twigs, leaves fallen on ground) nearby for utilizing in biogas plant. It is designed assuming the energy needs of a family of 6 members. It will not be an optimal solution if the family has more than 6 members or there is a greater number of adults in the family than assumed. (Average energy needs of an adult are more than that of kids). Energy requirements for appliances such as television, refrigerator, air-conditioner etc. are not included in the analysis as these will be considered as “luxury items” considering the location to be an isolated forest. The supplier information and component availability is mentioned keeping India in mind. Hence, the components might not be available outside India. It has provisions if there is lack of proper sunlight for a few days, but prolonged periods of improper sunlight will lead to relying on fuel generator for energy demands. It has been assumed that there will not be any kind of hindrance in the path of sunlight incident on solar panels.

---

## Requirements

In the following section, we give a brief on various traits that our off-grid living solution must possess. We also jot down the various requirements that will be needed to ensure our proposed solution is as efficient and trustworthy as possible.

<p align="center">
	 <img src="https://raw.githubusercontent.com/CrypticPoet/off-grid-energy-design/master/Mindmaps/requirements.png" alt="Mindmap for Requirements"  width=450/> 
	 <figcaption align="center">Mindmap for Requirements</figcaption>
</p>

---

### Base Setup

One of the main requirements for the system is that it is reasonably easy to set up so that minimum technical assistance is required for the same, and the house owner can perhaps even set it up himself.
These requirements require the system to be:

-   **Easy to implement**: The system should be easy to implement so that any person with little or no technical experience can implement and install the system by following simple instructions. The system also needs to be easy to repair so that there are minimum power cuts.
-   **Low maintenance**: The system needs to require low maintenance so that the user does not have to get it serviced frequently. If possible, it should be such that the users can themselves service it.
-   **Set-up time**: The system should be able to be set up within a short duration of time (3-4 days) to avoid any inconvenience in the form of power breaks to the users during the setup.
-   **Easy to Remove**: The system should be easy to remove so that the user can remove the setup if they want to relocate to a new location. For this, the system should also allow easy transportation over long distances so that the user can take it with themselves
-   **Long-term sustenance**: Should sustain itself for long periods of time even in the absence of production (no solar production during winters).
-   **Backup Generator**: Need in cases of emergency, high power usage situations, and 2nd option for achieving the above goal (long-term sustenance).

---

### Basic Requirements

Some of the basic user requirements are:

1. **Accommodation**: The energy generated should be able to satisfy the needs of a family of six.

2. **Power Requirements**: The daily power requirement is approximately 24-25 kWh. The explanation for the same can be seen as follows:

<!-- # table1 -->
| S. No.                  | Appliance                 | Number of Appliances | Power Consumed by Each | Daily Time Consumption | Total Energy Consumed  | Explanation                                                       |
| ----------------------- | ------------------------- | -------------------- | ---------------------- | ---------------------- | ---------------------- | ----------------------------------------------------------------- |
| 1                       | Tube Light                | 8                   | 0.02kW                | 8 Hours                | 0.02\*4\*8=0.64kWh    | Assuming, on average, 4 lights out of 8 are ON for 8 hours.      |
| 2                       | LED Bulbs                | 4                   | 0.04kW                | 6 Hours                | 0.04\*3\*6=0.72kWh    | Assuming, on average, 3 lights out of 4 are ON for 6 hours.      |
| 3                       | Ordinary ceiling fan      | 6                    | 0.075kW                | 10 Hours               | 0.075\*4\*10=3kWh      |  Assuming, on average, 4 fans out of 6 are ON for 8 hours.  Only in Summers    |
| 4                       | Induction Stove              | 1                    | 1.8kW                  | 2 Hour                 | 1.8\*1\*2=3.6kWh         |                                                            |
| 5                       | Water Heater              | 2                    | 1.5kW                  | 1 Hour                 | 1.5\*2\*1=3kWh         | Only in Winters                                                                  |
| 6                      | Laptop Adapater         | 1                    | 0.045W                  | 10 Hours                | 0.045\*1\*10=0.45kWh       |                                                                   |
| 7                      | Miscellaneous (e.g TV 50 inch 0.1kW, PC 0.2kW)   |                      |                        |                        | 1kWh                   | Assuming extra consumption to be 1kWh per day. |
| Daily power requirement | Summers//Winters          |                      |                        |                        | 9.41//9.41 kWh ± 10% |
                                                                 Table 4: Power Requirements

3. **Budget**: The cost of manufacturing should not be more than Rs. 3,00,000.

4. **Backup**: In case of any system failure, there must be a fuel generator strong enough to provide backup for the basic energy requirements.

5. **Water Requirements**: The energy should sustain the operation of bore pumps to satisfy the water requirements of the house.

6. **Season**: There should be suitable alternatives to meet the energy requirements with changing seasons such as substitutes for solar panels during the winter season.

7. **Maintenance**: The system should require low maintenance in terms of system longevity. This should also be easy-to-handle by the residents themselves.

8. **Efficiency**: The batteries used to store energy should be efficient in order to ensure longer periods of usage. The appliances can also be used in an energy saver mode.

9. **Safety**: There must be fuses and master controller or circuit breakers (MCB) in order to ensure safety in case of fluctuations or malfunction.

10. **Monitoring**: The system should have a provision for monitoring the total energy consumed by all major appliances.

11. **Remote Access**: The system should be equipped with a remote accessing facility of solar panels as well as the appliances.

---

### Technical Requirements

Various technical apparatus and tools required to acheive our goal are:

1. **Solar Panels**: An assembly of photo-voltaic cells mounted and connected to each other used to harness solar energy and convert it into electrical energy. The electricity produced by solar panels is DC in nature. Some factors characteristic of a good solar panel are low price, high efficiency, low-temperature coefficient.

2. **Batteries**: Deep cycle batteries are used in order to store energy produced by the solar panels during the day to use during the night. In order to have a long battery life, we wish to have a battery with a larger number of charge/recharge cycles.

3. **Inverter**: Solar panels generate DC electricity which needs to be converted to AC electricity needed by many common household appliances which are achieved by using an inverter. We wish to have an inverter that is cheap and provides high efficiency in converting DC to AC with minimal power losses.

4. **Mounting apparatus**: Solar panels are usually connected to each other and then subsequently mounted either on the roof or on the ground. The panels must be mounted so as to ensure cooling airflow and in a manner where maximum sunlight is available to the panels throughout the day.

5. **Charge Controllers**: Charge controllers are used to control the amount of current fed into the battery by the solar panels.This ensures the batteries are not overcharged during the day and don't leak current back to the panels during the night. There are two types of charge controller devices available - PWM and MPPT of which MPPT though more expensive is upto 30% more efficient than PWM charge controllers.

6. **Battery Monitor**: This meter would allow us to get an idea of how much power is being generated, how much amount we are saving by using solar panels and helps monitor which appliances use more power to manage energy utility.

7. **Backup Generator**: In case of off-grid systems backup power supply like a generator can serve as an alternate power supply in case of cloudy days, high demand or other unforeseen circumstances. The environmental impact of the generator could be reduced by using alternative fuels like biodiesel.

8. **Disconnects**: These are manual switches that enable us to cut off the power supply to and from the inverter in case of maintenance. This prevents current from flowing beyond the switch to some damaged component.

9. **Smart Lights**: Smart lights can be used to track Daytime and thus switching on/off lights at necessary places accordingly. This would allow us to smartly switch off electrical appliances not being used in order to save energy.

10. **Wires**: Insulated copper or aluminum wires needed to connect various electrical components

11. **Bio Gas plant**(optional): A biogas plant can be set up to harness energy out of the biodegradable waste that is produced in the household. This can later be used in the form of cooking gas or processed through a biogas generator for an alternative electricity source.

---

## Specifications

In the following section, we give a brief on various specifications of the components that we will be using in our off-grid living solution. We also mention their properties and why we have chosen them along with the best quotation available for each component.

<p align="center">
	 <img src="https://raw.githubusercontent.com/CrypticPoet/off-grid-energy-design/master/Mindmaps/specifications.png" alt="Mindmap for Specifications"  width=450/> 
	 <figcaption align="center">Mindmap for Specifications</figcaption>
</p>

---

### Electrical Specifications
#### Battery
##### Luminous Red Charge RC 18000 150 Ah Battery

<img src="https://m.media-amazon.com/images/I/61gCRXU1iMS._SL1500_.jpg" alt="battery" width="250" height="250"/>

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
| Cost                            |  &#8377;12150 X 3 = &#8377;36450                           |
                                 Table 5: Specifications of Battery

---

#### Backup Generator

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
--                         Table 6: Specifications of Backup Generator

[Product Link](https://www.indiamart.com/proddetail/1-kva-portable-petrol-generator-23901047630.html)

---

#### Hybrid Solar Inverter (Built in Solar Charge Controller)
##### 3KVA/ 36 V Off Grid Solar Inverter

<img src="https://cdn.shopify.com/s/files/1/0270/1757/6533/products/1_4_1280x.jpg" alt="battery" width="400" height="500"/>

Luminous Solar Hybrid Inverter 3kVA/36 is an off grid hybrid solar inverter which allows smart management of Solar Power, Grid Supply and Battery to deliver uninterrupted power for all electrical appliances. It comes built in with an mppt technology based Solar Charge Controller that converts solar energy into electricity and stores power. 
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
 --                         Table 7: Specifications of Hybrid Solar Inverter



#### Solar Charge Controller

Charge controllers are used to control the amount of current fed into the battery by the solar panels. This ensures the batteries are not overcharged during the day and don't leak current back to the panels during the night. So, Solar Charge Controller must be compatible with solar panel and the battery bank. Our Hybrid inverter comes built in with an MPPT Charge controller which is more efficient at DC Conversion compared to older PWM technology.

##### Sizing
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
--                        Table 8: Specifications of  Solar Charge Controller

[Product Link](https://www.urbanurja.com/products/luminous-solarverter-pro-pcu-3-kva-36v-mppt-solar-inverter#)

---

#### High Efficiency Solar Panels

Solar panels collect clean renewable energy in the form of sunlight and convert that light into electricity which can then be used to provide power for electrical loads. 

The panels which we're using, are based on [mono PERC cells](https://regenpower.com/news/why-choose-mono-perc-panels-rooftop-solar/), which results into higher electricity generation due to higher light absorption per unit area, when compared to traditional panels.
 
It also paves the way for more power output per panel, which means less number of panels are required for a given power requirement. It means less expenditure for 
[panel mounts](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSWhB7u8DxJiUJTM2uH5U-6Ml3h3SoByqJd8g&usqp=CAU).

<img src = 
"https://cdn.shopify.com/s/files/1/2980/5140/products/dimension_fcef7a49-c267-4a58-b571-90de3319af24_1000x.jpg?v=1618825077" height=500>

We'll be using 4 such panels in our system.

| Specification (Single panel) | Value         |
| ---------------------------- | ------------- |
| Cost                         | &#8377;20,000 |
| Operating Voltage            | 24V           |
| Dimensions                   | 6.9ft X 3.4ft |
| Manufacturer                 | Loom Solar    |
| Rated Output Power (Peak)    | 440W          |
| Output Voltage at max. power | 42V           |
| Output Current at max. power | 10.5A         |
--               Table 9:  Specifications of High Efficiency Solar Panels


*Above electrical data is for, Irradiance: 1000W/m² and Cell Temperature:25°C*

[Product Link](https://www.loomsolar.com/products/loom-solar-panel-shark-super-high-efficiency-module)

---

#### Wires
##### Solar DC Cable
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
--               Table 10: Specification of Solar DC Cable

[Product Link](https://www.amazon.in/Microtek-Solar-Cable-Protected-15Meter/dp/B08BBYX28X/)

#####  Household connection wires
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
--                               Tbale 11 : Specification of Household Connection Wires

[Product Link](http://dl.flipkart.com/dl/havells-hrfr-pvc-2-5-sq-mm-black-90-m-wire/p/itmbcd2c1b016975?pid=ELWFHWS4S7YZAAQ7&cmpid=product.share.pp)


---

#### Safety Measures

##### AC Circuit Breaker
 
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
 --                              Table 12: Specification of AC Circuit Breakers
 [Product Link](https://www.amazon.in/Siemens-Pole-White-1-Piece-5SL64637RC/dp/B01D4QL6RC)

##### DC Circuit Breaker

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
--                                    Table 13: Specification of DC Circuit Breaker

[Product Link](https://www.amazon.in/FEEO-63A-Double-Pole-MCB/dp/B01LF8E0T2/ref=sr_1_3?crid=2B9MK4LCK4WR2&keywords=feeo&qid=1642516418&sprefix=dc+circuit+breaker%2Caps%2C864&sr=8-3)

##### DC Surge Protection Device

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
--           Table 14 : Specification of DC surge protection device
[Product Link](https://www.amazon.in/Kenbrook-Solar-Elmak-Protection-Device/dp/B09NTQDJGP/ref=sr_1_2?crid=108RSYE3E2S5V&keywords=solar%2Bsurge%2Bprotection&qid=1642516582&sprefix=solar%2Bsurge%2Bprotectio%2Caps%2C767&sr=8-2&th=1)

#####  Porcelain Fuse
<img src = "https://m.media-amazon.com/images/I/71b9tS1f2bL._SL1500_.jpg" width = 300>

| Specification      | Value               |
| ------------------ | ------------------- |
| Brand              | Anchor              |
| AC Adapter Current | 32 A                |
| Voltage            | 415 V               |
| Material           | Ceramic             |
| Dimensions         | 10 cm X 5 cm X 5 cm |
| Cost               | &#8377;185          |
--                                                 Table 15 : Specification of porcelain fuse

[Product Link](https://www.amazon.in/Anchor-9311-Porcelain-Pilot-Ivory/dp/B00V4VJ7IK/ref=sr_1_12?crid=NPAHCXCDE79L&keywords=fuses&qid=1642478482&sprefix=fuses%2Caps%2C376&sr=8-12)

---

#### MC4 Connectors
##### MC4 Solar Panel Connectors

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
--                              Table 16: Specification of MC4 solar panel connectors

[Product Link](https://www.amazon.in/Kenbrook-Solar-Connector-Panel-Connection/dp/B08VNW7DLP/)

##### 4 in 1 T4 Connector

T4 Connector is required to connect the 2x4 parallel solar panel array to the solar charge controller. The T4 connector also comes with UV Resistance, anti flame and water resistance

<img src="https://m.media-amazon.com/images/I/81v6jkEqD4L._SL1500_.jpg" height="300">

| Specification | Value                                            |
| ------------- | ------------------------------------------------ |
| Brand         | Kenbrook                                         |
| Material      | Copper (Tin Plated) \| PPO + PA (Outer Covering) |
| Dimension     | 17 x 17 x 2 cm                                   |
| Quantity      | 2 sets                                           |
| Cost          | &#8377;799                                       |
--                               Table 17: Specification of T4 connector

[Product Link](https://www.amazon.in/Kenbrook-Solar-T4-Connector-Support/dp/B09BK14GVL/ref=asc_df_B09BK14GVL/?tag=googleshopdes-21&linkCode=df0&hvadid=397082397254&hvpos=&hvnetw=g&hvrand=15819054729291385736&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=1007805&hvtargid=pla-1394527439693&ext_vrnc=hi&th=1)

---

### Mechanical Specifications
#### Solar Panel Mounts

Panel mounts are used to fix solar panels on surfaces like roofs, building facades, or ground. The panel array is mounted with each panel aligned at an angle. This angle is variable and mounts should be bought according to the type of rooftop. We'll be using ones with 25° inclination.

<img src = 
"https://cdn.shopify.com/s/files/1/2980/5140/products/LoomSolar2rowDesign4PanelStand375watt_2_700x.jpg?v=1624973202" height=500>

We'll be using 1 such mount for our system, which consists of 4 panels.

| Specification (Single unit)  | Value           |
| ---------------------------- | --------------- |
| Cost                         | &#8377;12,000   |
| Inclination                  | 25°             |
| Dimensions(Leg)              | 150cm X 60cm    |
| Manufacturer                 | Loom Solar      |
| Weight                       | 50kg            |
| Material                     | Galvanised Iron |
| Holding Capacity             | 4 Panels        |
--                         Table 18 : Specification of solar panel mounts
[Product Link](https://www.loomsolar.com/collections/solar-panel-stand/products/loom-solar-2-row-design-4-panel-stand-375-watt)

---

## Design

Here, we give a brief on how the off-grid energy solution is expected to look like after assembling the various components. We also give design blueprints and wiring diagrams wherever required, making necessary but plausible assumptions about the geography and architecture of the house.

<p align="center">
	 <img src="https://raw.githubusercontent.com/CrypticPoet/off-grid-energy-design/master/Mindmaps/design.png" alt="Mindmap for Design"  width=450/> 
	 <figcaption align="center">Mindmap for Design</figcaption>
</p>

### CAD/Assembly
The following image is the 3-D diagram of the designed house.
<p align="center">
	<img src="https://raw.githubusercontent.com/CrypticPoet/off-grid-energy-design/master/CAD%20Design/home_wireframe_front.jpg" alt="Front View" width=500>
	<figcaption align="center">Front View</figcaption>
</p>

<p align="center">
	<img src="https://raw.githubusercontent.com/CrypticPoet/off-grid-energy-design/master/CAD%20Design/home_wireframe.jpg" alt="Side view" width=500/> 
	 <figcaption align="center">Side View</figcaption>
</p>

<p align="center">
	 <img src="https://raw.githubusercontent.com/CrypticPoet/off-grid-energy-design/master/CAD%20Design/home_wireframe_top.jpg" alt="Top View" width=500/>
	 <figcaption align="center">Top View</figcaption>
</p>

<p align="center">
	 <img src="https://raw.githubusercontent.com/CrypticPoet/off-grid-energy-design/master/CAD%20Design/home_orthographic.jpg" alt="Isometric view"  width=500/> 
	 <figcaption align="center">Orthographic View</figcaption>
</p>


The components of our energy solution are detailed as follows:

***Label 1*** - Solar Panels
Solar panels to take the solar energy and give a DC current.

<p align="center">
	<img src="https://raw.githubusercontent.com/CrypticPoet/off-grid-energy-design/master/CAD%20Design/solar_side.jpg" alt="Side view" width=300/> 
	<img src="https://raw.githubusercontent.com/CrypticPoet/off-grid-energy-design/master/CAD%20Design/solar_front.jpg" alt="Front View" width=300/>
	<img src="https://raw.githubusercontent.com/CrypticPoet/off-grid-energy-design/master/CAD%20Design/solar_top.jpg" alt="Top View" width=300/>
	<figcaption align="center">Side View, Front View and Top View (L to R)</figcaption>
</p>

***Label 2*** - Inverter  
Takes the solar DC current, and supply it power supply as well as store it in battery.

<p align="center">
	<img src="https://raw.githubusercontent.com/CrypticPoet/off-grid-energy-design/master/CAD%20Design/inverter_side.jpg" alt="Side view" width=300/> 
	<img src="https://raw.githubusercontent.com/CrypticPoet/off-grid-energy-design/master/CAD%20Design/inverter_front.jpg" alt="Front View" width=300/>
	<img src="https://raw.githubusercontent.com/CrypticPoet/off-grid-energy-design/master/CAD%20Design/inverter_top.jpg" alt="Top View" width=300/>
	<figcaption align="center">Side View, Front View and Top View (L to R)</figcaption>
</p>

***Label 3*** - Battery  
Stores the solar converted electrical energy for further use when solar power cannot be harnessed e.g. Night. 

<p align="center">
	<img src="https://raw.githubusercontent.com/CrypticPoet/off-grid-energy-design/master/CAD%20Design/battery_side.jpg" alt="Side view" width=300/> 
	<img src="https://raw.githubusercontent.com/CrypticPoet/off-grid-energy-design/master/CAD%20Design/battery_side.jpg" alt="Front View" width=300/>
	<img src="https://raw.githubusercontent.com/CrypticPoet/off-grid-energy-design/master/CAD%20Design/battery_top.jpg" alt="Top View" width=300/>
	<figcaption align="center">Side View, Front View and Top View (L to R)</figcaption>
</p>

---

### Wiring Diagram

The next step is to realize the design using all the components mentioned in the specifications by appropriately connecting them. The diagram below shows the connections for the same. 

<p align="center" id="wiring"><img src="https://raw.githubusercontent.com/CrypticPoet/off-grid-energy-design/master/Images/wiring_diagram.jpg" width=512></p>

The solar panels are connected in a 2x2 fashion using the MC4 Panel Connectors. These are then connected to a DC Circuit Breaker using T4 connectors. The wires then go via a DC Surge Protector to the invertor which is connected to a series combination of 3 batteries of 12V each. The output of the invertor then goes to an AC circuit breaker which has also been connected to the generator for backup. This is finally connected to the MCB inside the house.

---

## Cost Analysis

| Component | Price | Quantity | Total Price | Vendor |
|------------------|--------------|--------|-----------------|--------------|
|Battery | &#8377;12,150 | 3 | &#8377;36,450 | [Product Link](https://www.amazon.in/LUMINOUS-RC-18000-Tubular-Battery/dp/B0713S16VF)|
|Backup Generator| &#8377;22,900| 1 | &#8377;22,900 | [Product Link](https://www.indiamart.com/proddetail/1-kva-portable-petrol-generator-23901047630.html)|
|Hybrid Solar Invertor| &#8377;39,950 |1 | &#8377;39,950 |[Product Link](https://www.urbanurja.com/products/luminous-solarverter-pro-pcu-3-kva-36v-mppt-solar-inverter) |
|Solar Panels | &#8377;20,000 | 4 | &#8377;80,000| [Product Link](https://www.loomsolar.com/products/loom-solar-panel-shark-super-high-efficiency-module)|
|Solar DC Cable (15 m) | &#8377;1,990 | 2 | &#8377;3,980 | [Product Link](https://www.amazon.in/Microtek-Solar-Cable-Protected-15Meter/dp/B08BBYX28X/)|
|Household connection wire (90 m) | &#8377;2,949 | 1 | &#8377;2,949 | [Product Link](http://dl.flipkart.com/dl/havells-hrfr-pvc-2-5-sq-mm-black-90-m-wire/p/itmbcd2c1b016975?pid=ELWFHWS4S7YZAAQ7&cmpid=product.share.pp)|
| AC Circuit Breaker | &#8377;1,500 | 1 | &#8377;1,500 | [Product Link](https://www.amazon.in/Siemens-Pole-White-1-Piece-5SL64637RC/dp/B01D4QL6RC)|
|DC Circuit Breaker | &#8377;999 | 2 | &#8377;1,998 | [Product Link](https://www.amazon.in/FEEO-63A-Double-Pole-MCB/dp/B01LF8E0T2/ref=sr_1_3?crid=2B9MK4LCK4WR2&keywords=feeo&qid=1642516418&sprefix=dc+circuit+breaker%2Caps%2C864&sr=8-3)|
|DC Surge Protection Device | &#8377;799 | 1 | &#8377;799 | [Product Link](https://www.amazon.in/Kenbrook-Solar-Elmak-Protection-Device/dp/B09NTQDJGP/ref=sr_1_2?crid=108RSYE3E2S5V&keywords=solar%2Bsurge%2Bprotection&qid=1642516582&sprefix=solar%2Bsurge%2Bprotectio%2Caps%2C767&sr=8-2&th=1)|
|Porcelsian Fuse | &#8377;185| 1 | &#8377;185 | [Product Link](https://www.amazon.in/Anchor-9311-Porcelain-Pilot-Ivory/dp/B00V4VJ7IK/ref=sr_1_12?crid=NPAHCXCDE79L&keywords=fuses&qid=1642478482&sprefix=fuses%2Caps%2C376&sr=8-12)|
| MC4 Solar Panel Connectors | &#8377;449 | 2 | &#8377;898 | [Product Link](https://www.amazon.in/Kenbrook-Solar-Connector-Panel-Connection/dp/B08VNW7DLP/)|
|4 in 1 T4 Connector | &#8377;799 | 2 | &#8377;1,598 | [Product Link](https://www.amazon.in/Kenbrook-Solar-T4-Connector-Support/dp/B09BK14GVL/ref=asc_df_B09BK14GVL/?tag=googleshopdes-21&linkCode=df0&hvadid=397082397254&hvpos=&hvnetw=g&hvrand=15819054729291385736&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=1007805&hvtargid=pla-1394527439693&ext_vrnc=hi&th=1)|
|Solar Panel Mount | &#8377;18,000 | 1 | &#8377;18,000 | [Product Link](https://www.loomsolar.com/collections/solar-panel-stand/products/loom-solar-2-row-design-4-panel-stand-375-watt)|
| Installation Cost| | | &#8377;12,320 | [Product Link](https://www.loomsolar.com/blogs/collections/solar-panel-installation-cost-in-india)|
| Electrician Charges| | | &#8377;3,000 | [Product Link](https://www.urbancompany.com/request/electricians)|
|Total Price | | | &#8377;2,11,527 |
-							   Table 19 : Cost Analysis
---

## Reuse of Materials

- **Solar Panels** 

    - **Create Greenhouses:** A greenhouse is generally made up of glass and so are solar panels. We can easily make use of them and keep our plants warm throughout the cooler months. The junction box and frame are separately removed to recover copper and aluminum. Both of these materials are 100% reusable.
    
    - **Use Them as Insulation:** We can use our old solar panels to create walls and insulation to make our home even more eco-friendly.
    
- **Battery**

    - **Solar Powered Generator:** We can make a solar-powered generator using old or dead batteries and this could be sufficient for 25 hours if we use energy saving bulbs.
    
    - **A Portable Rechargeable Lighting System:** We can make portable rechargeable lighting systems using old or dead batteries. All we need is – LED plate, On/off switch, Diode IN4007, 1000 Ohms Resistor, Red LED light, Charging socket, Superglue, Soldering tool.

- **Mounting apparatus**

    - These are structures made of galvanized iron and can be used for mounting other solar panels or can also be sold as scrap iron to manufacture other equipment.

- **Backup Generator**

    - Generator is always needed for family reunions, weddings, cookouts and other outdoor parties to provide power.
    
    - Generators can be used to store the energy captured by solar panels to be used later instead of sending it back to the grid.

- **Disconnects**
    
    - Circuit breaker is reusable and can be reset after it has tripped due to overloads.

- **Inverter**
    
    - The DC electricity generated by the solar panels is converted into AC using this inverter, for powering all electrical appliances, lighting, power tools etc. in the house.

---

## Attributions

While designing this solution for off grid living, we used a number of softwares/extensions for various aspects of the project. These include -

- [**WordCounter**](https://wordcounter.net/): For obtaining the document text statistics
- [**Readability Check (VS Code Extension)**](https://marketplace.visualstudio.com/items?itemName=jemcclin.readabilitycheck): For obtaining readability indices scores for the document
- [**ProjectLibre**](https://www.projectlibre.com/): For project management tools
- [**Draw.io**](https://app.diagrams.net/): For creating mind maps
- [**Tinkercad**](https://www.tinkercad.com/): For designing 3D models and plans for the project
- [**GLC Player**](https://sourceforge.net/projects/glc-player/): For exporting the OBJ models from Tinkercad to images
- [**Excalidraw**](https://excalidraw.com/): For designing the circuit diagram for the project
- [**Zotero**](https://www.zotero.org/): For collecting and managing references

---

## References

---
