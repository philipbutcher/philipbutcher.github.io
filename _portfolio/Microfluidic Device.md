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
Microfluidic devices, which operate on a microscopic scale to precisely manipulate small fluid volumes, are vital in biomedical, chemical, and environmental applications. These devices provide exceptional control over fluid flow, making them particularly effective for separating particles based on size, density, or other physical properties. As part of a class design project, a microfluidic device was developed to separate particles measuring 165 microns and 550 microns in diameter. The device leverages a phenomenon known as pinched flow fractionation, incorporating a narrow pinch zone that transitions into a wider channel to achieve particle separation. Within the confined pinch zone, particles are aligned and organized according to their size. As the channel expands, the particles diverge along distinct trajectories based on their dimensions, enabling highly efficient and precise separation.
## Design Process

* **Design** Using Fusion 360, a mold was designed and created to cast the device. With the goal of separating different sized particles, the instrument features two inlets for liquid to flow into. One inlet introduces a solution containing the mixed particles, while the other carries a buffer solution. These streams merge at a 1.5 mm-wide "pinched" segment, where particles are aligned by size: larger particles flow toward the center of the channel, while smaller particles remain closer to the inner wall. Following this, the channel expands into a 14 mm-wide zone that further separates the particles as they continue along distinct trajectories. Forked outlets at the end of the expansion zone collect the particles based on their positions, enabling effective separation and collection.
* **Printing and Preparation** With the CAD model complete, the mold could be printed. Using the Formlabs Form 4 resin printer, a highly accurate model was printed and cured using UV light. From there, the mold was coated in a thin layer of Parylene. This acts as a barricade between the epoxy resin and the filler of the mold, PDMS (polydimethylsiloxane). The mixing of these two could result in lost features and incomplete curing. After the Parylene was applied, PDMS was poured into the mold, and the device was created. Two thin sheets of glass were added to each side, and the device was ready for testing.
* **Useability** To test the device, syringe pumps of the mixed particle solution and buffer solution were attached to hoses at each of the inlets. A ratio of approximately 1:9 for particle vs buffer flow rate was set. This high ratio compresses the fluids even more, pushing the smaller particles closer to the outer wall and creating more predictable particle separation. A video of a fellow students device can be found [here](https://www.youtube.com/watch?v=--6JoKgJHCo).


## CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH286ddQT78850c0d8a45857eb674db70423?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>
{% include gallery %}



