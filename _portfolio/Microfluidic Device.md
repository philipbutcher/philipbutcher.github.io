---
title: "Microfluidic Device"
excerpt: "Resin printed device to separate particles at the micron scale"
header:
  teaser:/assets/img/Device.jpg

gallery:
  - url: /assets/img/Device.jpg
    image_path: /assets/img/Device.jpg
    alt: "Microfluidic Device"
  - url: /assets/img/Angled View Microfluid.png
    image_path: /assets/img/Angled View Microfluid.png
    alt: "CAD Model of Mold"
  - url: /assets/img/Top View Microfluid.png
    image_path: /assets/img/Top View Microfluid.png
    alt: "Top View of CAD Model"
    

---

<img src="/assets/img/Angled View Microfluid.png" alt="Philip Butcher" style="width:900px;"/>

## About
Microfluidic devices are systems that can manipulate tiny volumes of fluid at the micro-scale level, allowing for precise control over fluid flow and enabling applications across biomedical, chemical, and environmental fields. Real world examples can include bloodwork, drug development, cell separation, and more. Homogeneous mixing in microfluidics is especially common as the consistent mixing of reagents with biological samples is essential to achieve accurate and reproducible results. Yet, achieving effective mixing in microfluidic devices presents a unique challenge due to the dominance of laminar flow at this scale. In the microchannels of the device, liquid tends to flow in parallel layers without the turbulence that typically creates a mixing effect. Consequently, to achieve homogenous mixing, microfluidic designs must incorporate features such as winding channels, staggered obstacles, or split paths to promote diffusion and enhance mixing efficiency in the confined spaces of a microfluidic device. As a design challenge for a class, a microfluidic device was designed and printed with the ability to separate particles of 165 and 550 microns in diameter.
## Design Process

* **CAD Modeling** Using Fusion 360, a mold was created to cast the device in. With the goal of separating different sized particles, the device features two inlets for liquid to flow into. One of these will hold particles suspended in a solution, and the other is a buffer. The two inlets combine at a “pinched” segment. This thin pathway compresses the liquid flow, until it reaches a wide opening. This opening lets the liquid expand, and because of the different weights of the two particles, their trajectories are different. The smaller particles fly outward to the walls of the device, whereas the larger particles stay closer to the middle. Now flowing in parallel, the particles can enter their respective outlets, ensuring accurate particle separation.
* **Printing and Preparation** With the CAD model complete, the mold could be printed. Using the Formlabs Form 4 resin printer, a highly accurate model was printed and cured using a UV light. From there, the mold was coated in a thin layer of Parylene. This acts as a barricade between the epoxy resin and PDMS (polydimethylsiloxane), as the mixing of these two could result in lost features and incomplete curing. Then, PDMS was poured into the mold, and the device was created. Two thin sheets of glass were added to each side, and the device was ready for testing.
* **Useability** To test the device, syringe pumps of the mixed particle solution and buffer solution were attached to hoses at each of the inlets. A ratio of approximately 1:9 for particle vs buffer flow rate was set. This high ratio compresses the fluids even more, pushing the smaller particles closer to the outer wall and creating more reliable particle separation. A video of a fellow students device can be found [here.](https://www.youtube.com/watch?v=--6JoKgJHCo)).

## CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH286ddQT78850c0d8a45857eb674db70423?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>
{% include gallery %}



