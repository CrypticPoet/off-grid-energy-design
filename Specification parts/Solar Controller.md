### Solar Charge Controller
Charge controllers are used to control the amount of current fed into the battery by the solar panels.This ensures the batteries are not overcharged during the day and don't leak current back to the panels during the night.
So, Solar Charge Controller must be compatible with solar panel and the battery bank.
We will be using MPPT controllers, as they are more efficient than PWM Controllers.

#### Sizing
Sizing of a controller depends on three factors
- Solar panel array’s maximum open-circuit voltage (Voc)
- Total Power rating of Solar panel array
- Battery Bank Voltage

**Solar panel array’s maximum open-circuit voltage (Voc)**: The 8 solar panels are arranged in a 2x4 array, such that 4 pairs of solar panels are in parallel, with each pair in series. Each Solar panel has a open circuit voltage of 49V. So, the maximum open circuit voltage of solar panel is 49x2= 98V.

**Total Power rating of Solar panel array**: Since, we are using 8 solar panels with 440 W power rating.Hence, the total power rating of Solar panel array is 3520W.

**Battery Bank Voltage**: Battery Bank Volatge of our system is 48V.

Now, from power rating and battery bank voltage, we can calculate the required Ampere rating of the controller, which is equal to (power rating/Bank Voltage).
So, the required Ampere rating is 73.33A.
The required maximum input Voc of controller = maximum open circuit voltage of solar panel.

Hence, Our Controller must have atleast 98V input Voc rating and 73.33A current rating.
We select the controller such that these two figures slightly exceed the requirements to build a safety margin.


<img src="https://m.media-amazon.com/images/I/716mOCHk-ZL._SL1500_.jpg" alt="Charge Controller" width="334" height="334"/>

| Specification           | Value                          |
| ----------------------- | ------------------------------ |
| Type                    | MPPT                           |
| Maximum Input Voc       | 210V                           |
| Ampere Rating           | 80A                            |
| Compatible Battery Bank | 12V/24V/36V/48V                |
| Dimensions              | 35.5 x 21.5 x 14.2 Centimeters |
| Cost                    | Rs. 17,599                     |

<!---This comment includes link for reference: https://www.amazon.in/ASHAPOWER-Controller-NEON-80Ampere-Selection/dp/B09GPHFCS9/ref=sr_1_1?crid=2F23H3F4Z2Y6F&keywords=48V+80A+solar+charge+controller&qid=1642445019&sprefix=48v+0a+solar+charge+controller%2Caps%2C608&sr=8-1 --->










