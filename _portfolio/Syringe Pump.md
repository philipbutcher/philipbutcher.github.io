---
title: "Syringe Pump"
excerpt: "Programmable Syringe Pump Design For A Class Project"
header:
  teaser: /assets/img/Syringe_Pump_Front.jpg

gallery:
  - url: /assets/img/Syringe_Pump_Front.jpg
    image_path: /assets/img/Syringe_Pump_Front.jpg
    alt: "Real Life Syringe Pump"
  - url: /assets/img/Syringe_Pump_CAD.png
    image_path: /assets/img/Syringe_Pump_CAD.png
    alt: "Syringe Pump CAD Model"
  - url: /assets/img/Syringe_Pump_CADinside.png
    image_path: /assets/img/Syringe_Pump_CADinside.png
    alt: "Arduino Inside of CAD Model"

---

<img src="/assets/img/Syringe_Pump_Front.jpg" alt="Philip Butcher" style="width:900px;"/>

## About
Syringe pumps are precision devices that use a motor-driven lead screw to deliver controlled amounts of fluid, ensuring accuracy and sterility. They are essential in medical and scientific fields, but despite their simple design, they can cost hundreds of dollars, making custom fabrication a worthwhile option. As a design challenge for class, a custom syringe pump was created using 3D-printed parts. A stepper motor drove the lead screw, and an Arduino program allowed for the adjustable flow rate. The pump featured user-friendly controls with indicator LEDs, a motor cutoff when out of liquid, and durable, water-resistant wiring. The entire build could be assembled and taken apart without glue or hammering of components.

## Features

* **Simple Construction** The syringe part was assembled with entirely off-the-shelf parts that cost signifcantly less than purchasing a premade syringe pump. The custom pump could be assembled and disassembled without any glue or fasteners, with an adjustable design in Fusion 360 to fit any parameters of an application
* **Adjustable Flow Rate** With simple programming within the Arduino code, the flow rate of the pump could easily be adjusted. The pump had a minimum flow rate of 1.75 mL/min and a maximum flow rate of 175 mL/minute with a 5 mL syringe installed. If desired, the flow rate could be changed to between 6-600 mL/min with a 20 mL syringe installed. Lastly, with microstepping, flow rates as low as 0.1 mL/min could be achieved. All within the Arduino code, an incredible range of flow rates can be incorprated to accommodate the variety of needs for a syringe pump.
* **Ease of Use** To allow for easy usability, a single button would start and stop the pump, and an LED would turn green when the machine was running, yellow when paused, and red when fully out of liquid. When out of liquid, a switch stopped the motor from continuing to run, and all electrical components were wrapped in heat shrink to protect against water damage.

## CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH286ddQT78850c0d8a4c61ba362f5253333?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

{% include gallery %}


#### Part List (Bought)

| Part Name                                     | Quantity|
| :--------------------------------------------:|:--:|
| 250 mm Lead Screw (2 mm Pitch 2 mm Lead)      | 1  |
| 250 mm Lead Screw (2 mm Pitch 8 mm Lead)      | 1  |
| 1/4"x8 mm Flexible Coupling                   | 1  |
| 200 mm Linear Rod (8mm diameter)              | 2  |
| LM8UU Linear Bearing (8 mm diameter)          | 2  |
| 2040 Aluminum Extrusion 1' Length             | 1  |
| Nema 17 Stepper Motor                         | 1  |
| AC-DC Power Supply Quad Output 5V 12V 24V 12V | 1  |
| Arduino Uno                                   | 1  |
| A4988 Stepper Driver                          | 1  |
| Small Breadboard                              | 1  |
| A4988 Stepper Driver                          | 1  |
| Panel Mount Latching Push Buttons             | 1  |
| Limit Switch                                  | 1  |
| RGB Common Cathod LED                         | 1  |

#### Part List (3D Printed)

| Part Nam                | Quantity|
| :----------------------:|:--:|
| Plastic Base            | 1  |
| Plastic Lid             | 1  |
| Logo Clip               | 1  |
| Title Page              | 1  |
| Syringe Carriage        | 1  |
| End Support             | 1  |
| Motor Mounting Plate    | 1  |
| Syringe Tip Support     | 1  |
| Syringe Plunger Support | 1  |

#### Code
The code can be found [here:](https://github.com/philipbutcher/philipbutcher.github.io/blob/main/assets/img/Arduino%20Code.txt)
