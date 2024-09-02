---
title: "Syringe Pump"
excerpt: "Programmable syringe pump"
header:
  image: /assets/img/Syringe_Pump_Front.jpg
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

| Part Name                                 | Quantity      |
| :----------------------------------------:|:-------------:|
| 200 mm Linear Rod (8mm diameter)          | right-aligned |
| LM8UU Linear Bearing (8 mm diameter)      | right-aligned |
