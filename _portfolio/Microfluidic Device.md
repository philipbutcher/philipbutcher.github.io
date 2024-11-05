---
title: "Microfluidic Device"
excerpt: "Resin Printed Device Capable of Separating Particles at the Micron Scale"
header:
  teaser: /assets/img/Device.jpg

gallery:
  - url: /assets/img/Device.jpg
    image_path: /assets/img/Device.jpg
    alt: "Microfluidic Device"
  - url: /assets/img/Mold.jpg
    image_path: /assets/img/Mold.jpg
    alt: "3D Printed Mold"
  - url: /assets/img/Angled View Microfluid.png
    image_path: /assets/img/Angled View Microfluid.png
    alt: "CAD Model of Mold"
  - url: /assets/img/Top View Microfluid.png
    image_path: /assets/img/Top View Microfluid.png
    alt: "Top View of CAD Model"
    

---

<img src="/assets/img/Angled View Microfluid.png" alt="Philip Butcher" style="width:900px;"/>

## About
Microfluidic devices, which operate at a microscopic scale to precisely manipulate small fluid volumes, play a critical role in biomedical, chemical, and environmental fields. They enable control over fluid flow, making them particularly useful for particle separation based on size, density, or other physical properties. For example, in biomedical research, separating specific cell types is critical for diagnostics and therapeutic monitoring. Similarly, environmental testing often requires separating microorganisms from water samples to assess contamination levels. As a design project for class, a microfluidic device was created to separate particles measuring 165 microns and 550 microns in diameter. Using a phenomenon called pinched flow fractionation, the device features a narrow pinch zone which expands to allow for the separation of particles. The narrow pinch zone confines and aligns particles based on size, allowing smaller particles to follow different flow paths than larger ones. As the channel widens, these paths help separate the particles effectively, ensuring distinct sorting based on size.

## Design Process

* **Design** Using Fusion 360, a mold was created to cast the device in. With the goal of separating different sized particles, the device features two inlets for liquid to flow into. One inlet holds the mixed particles suspended in solution, while the other is for a buffer solution. The two inlets combine at a “pinched” segment 1.5 mm in width. This channel aligns the particles based on size, with larger particles flowing in the middle of the path and smaller particles staying close to the inner wall. Then, an expansion zone of 14 mm helps separate these particles even further as they continue on their trajectories. Forked outlets separate the particles based on their location within the expansion zone, and the particles can be collected.
* **Printing and Preparation** With the CAD model complete, the mold could be printed. Using the Formlabs Form 4 resin printer, a highly accurate model was printed and cured using UV light. From there, the mold was coated in a thin layer of Parylene. This acts as a barricade between the epoxy resin and the filler of the mold, PDMS (polydimethylsiloxane). The mixing of these two could result in lost features and incomplete curing. After the Parylene was applied, PDMS was poured into the mold, and the device was created. Two thin sheets of glass were added to each side, and the device was ready for testing.
* **Useability** To test the device, syringe pumps of the mixed particle solution and buffer solution were attached to hoses at each of the inlets. A ratio of approximately 1:9 for particle vs buffer flow rate was set. This high ratio compresses the fluids even more, pushing the smaller particles closer to the outer wall and creating more predictable particle separation. A video of a fellow students device can be found [here](https://www.youtube.com/watch?v=--6JoKgJHCo).

## CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH286ddQT78850c0d8a45857eb674db70423?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>
{% include gallery %}



