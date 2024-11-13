---
title: "Multi-Material Pliers"
excerpt: "Functional Pliers Printed Out of TPU and PLA Plastic"
header:
  teaser: /assets/img/CAD Screenshot.png

gallery:
  - url: /assets/img/CAD Screenshot.png
    image_path: /assets/img/CAD Screenshot.png
    alt: "CAD Model of Pliers"
  - url: /assets/img/Pliers.JPEG
    image_path: /assets/img/Pliers.JPEG
    alt: "Photo of Pliers"


---

<img src="/assets/img/Pliers.JPEG" alt="Philip Butcher" style="width:600px;"/>

## About
Print-in-place parts are innovative designs that incorporate moving components or joints within a single 3D print job, removing the need for post-print processing. They are engineered with clearances and tolerances that allow sections to move freely once printed, enabling the creation of hinges, gears, springs, and other complex mechanisms to be utilized in a single device. Real-world examples of print-in-place parts can be found in custom prosthetics and medical devices, as well as in the aerospace and automotive industries where lightweight, compact, and easily assembled components are required. These prints often contain two or more materials. PLA or ABS plastics can be used as a durable, solid frame to offer the necessary strength and resilience needed for functional prototypes. Flexible materials like TPU can be used for shock absorption or elasticity, often being used as the spring component in these devices. The combination of these materials allows for intricate designs that would be challenging or impossible to achieve with traditional manufacturing.


## Design Process

* **Prototyping** With the design intent of making a pair of functional pliers, components were created using Fusion 360. First, rigid handles and plier tips were sketched and extruded, drawing inspiration from standard pliers you would find in any hardware store. However, a dovetail attachment allowed them to connect to a central pivot point. This pivot point features a square piece with the other dovetail design on all 4 sides. A grid like pattern was able to be added all within the 3D printer software, allowing for minimal design changes within the CAD itself. The handles and tips were made out of PLA to ensure a rigid, durable structure, while the middle joint was made out of TPU. When the handles were pressed together, it would pull the outer sides of the TPU middle apart. This had a counteracting effect on the plier tips, pushing them together, and allowing for an object to be picked up.
* **Print Settings** With the CAD model created, the different components were exported into SuperSlicer. The handles and tips were printed as standard. A 0.4 mm nozzle was used with rectilinear infill at 20% density. This allowed for rigid components that were still lightweight. However, for the TPU middle component, the printer settings were modified. While the rectilinear infill option was still used, the density was brought down to 8%. This created the thin diagonal lines needed for the correct flexing of the part. Furthermore, the top and bottom layers of the print were removed, and the perimeter walls were set to 6. This ensured a more solid exterior at the dovetails, as well as creating a uniform grid pattern throughout. For both prints, the bed distance was calibrated to ensure minimal gaps between the extrusion lines.
* **Specifications** The completed pliers have a jaw length of approximately 92 mm, with a distance of 16 mm between the ends of the tips. The handles have a maximum distance of 121 mm, with the entire length of the pliers being 280 mm. The pliers provide ample torque and accuracy, with the ability to pick up objects as small as an electrical resistor.


## CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH286ddQT78850c0d8a4ee3c61a144736d82?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

{% include gallery %}

<img src="/assets/img/gif.gif" alt="Philip Butcher" style="width:500px;"/>
