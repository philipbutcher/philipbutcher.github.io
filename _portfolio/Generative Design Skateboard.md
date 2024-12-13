---
title: "Generative Design Skateboard"
excerpt: "Skateboard Trucked Created Using Generative Design"
header:
teaser: /assets/img/Hanger Assembly.png

gallery:
  - url: /assets/img/Hanger Assembly.png
    image_path: /assets/img/Hanger Assembly.png
    alt: "CAD Model of Generated Skateboard Truck"
  - url: /assets/img/AlSi10Mg Rendering.png
    image_path: /assets/img/AlSi10Mg Rendering.png
    alt: " AlSi10Mg Skateboard Truck Rendering"
  - url: /assets/img/Nylon Rendering.png
    image_path: /assets/img/Nylon Rendering.png
    alt: " Nylon 12 Skateboard Truck Rendering"
  - url: /assets/img/Skateboard Rendering.jpg
    image_path: /assets/img/Skateboard Rendering.jpg
    alt: "Rendering of Completed Skateboard Assembly"
  - url: /assets/img/Real Life Truck.JPEG
    image_path: /assets/img/Real Life Truck.JPEG
    alt: "Real Life Attachment of Generative Design Truck"

---

<img src="/assets/img/Hanger Assembly.png" alt="Philip Butcher" style="width:900px;"/>

## Generative Design and SLS Printing
Generative design is a computer modeling technique that allows for the creation of mechanical parts using loads and obstacle geometries. In traditional CAD modeling, a 3-dimensional part is created through a series of sketches and extrusions, with manual calculations being formed to determine the necessary dimensions of a part. With generative design, the required loads (such as forces and torques) are added at different points in a 3-dimensional space, and machine learning algorithms generate a part to meet the given inputs. This generated component is typically stronger and lighter than a traditionally manufactured part. Yet, due to the complex geometry of the design, it can often be very difficult to machine in real life. Luckily, the combination of generative design and powder bed fusion manufacturing methods, such as selective laser sintering (SLS), have revolutionized the way complex components are designed and produced. SLS printing allows for any geometry to be achieved with the same level of ease. The unusual shape of these generative designed parts is no longer an issue, and as SLS technology continues to improve, we will see more and more parts being created and manufactured using generative design.

## Case Studies

Generative design allows engineers to leverage computational algorithms to create optimized structures based on specific constraints and objectives. Examples of this can be seen in a variety of industries, particularly in aerospace and automotive. For example, European plane manufacturer Airbus’ use of generative design for cabin partitions is the perfect case study. Through generative design, they were able to redesign their cabin partitions to be lighter, stronger, and simpler to assemble. Airbus achieved a 45% reduction in weight and consolidated over 100 parts into a single structure. This not only reduced material costs and fuel consumption but also streamlined their assembly processes. In the automotive industry, Ford has leveraged generative design and SLS printing to create optimized engine brackets. By incorporating generative algorithms, engineers developed brackets that are significantly lighter, stronger, and more compact compared to traditional designs. These improvements not only enhance fuel efficiency by reducing overall vehicle weight but also contribute to better vibration damping and structural performance. Lastly, in the biomedical field, medical technology company Stryker have used generative design to create patient-specific implants, including cranial plates and hip replacements. By leveraging this with powder bed fusion, Stryker has produced components with improved biomechanical compatibility and reduced material waste, ensuring better outcomes for patients. These examples underline how generative design and powder bed printing allow for the creation of geometries that are unachievable with traditional manufacturing methods, enabling advancements in sustainability, efficiency, and innovation.

## Applying Loads

One critical component of the generative design process is the assignment of loads and constraints. Without any guidance, the computer cannot create a suitable component. Therefore, careful parameters and inputs are given into the CAD assembly before the part is created. For example, this project revolved around the creation of a skateboard truck for an electric longboard. For the computer to successfully create this, many steps had to be followed. A constraint was added at the top of the truck (where it connects with the board). This makes sense, as many of the forces will travel through the truck into this one pivot point. Preserve geometries were added at the motor mount and wheel bearings. These tell the computer where to start and preserve material for the component. A center piece preserve geometry was also added for the through hole of the truck. On the other hand, obstacle geometries had to be added. These are areas where material cannot be added as it would interfere with other components such as the wheels, axle, deck, etc. With these geometries in place, loads could be incorporated into the build. A 2500 N downward force was placed on the center piece. This mimics the rider’s weight, accounting for added forces from jumping on the board. A 350 N force was added at both the left and right axles to mimic the force felt by turning. This was calculated assuming a 5 m turn radius with a 75 kg rider going ~11 mph. Other forces such as the motor weight, torque, and belt tension to power the wheels were also calculated and added.

## Nylon 12 vs. ALSi10Mg 

For this project, designs were created out of two materials, Nylon 12 and AlSi10Mg. Nylon 12, a polymer known for its flexibility and impact resistance, produced a lightweight and cost-effective design suitable for prototyping and low-load applications. It was chosen as this is the building material used in the Formlabs Fuse 1 SLS printer.
However, in reality a polymer would not be used to create a skateboard truck as it is not strong enough. Instead, an alloy such as AlSi10Mg could be used. This metal offers superior mechanical properties, including higher strength and thermal conductivity. This makes it ideal for manufacturing the truck hanger intended for functional testing. While it might be heavier than Nylon 12, its higher strength allowed for the truck to be slimmer in profile. Furthermore, its ability to withstand higher loads and resist deformation under torque made it the preferred choice for the final design. While AlSi10Mg could be costly to prototype with, once a final design is confirmed, it could easily be outsourced and metal 3D printed. 

## Generative Design Limitations

While generative design offers significant advantages over traditional manufacturing, it is not without its limitations. One key drawback is the reliance on accurate input parameters, including load cases and constraints. Inaccurate or overly conservative inputs can lead to suboptimal designs that are either overly complex or insufficiently robust. Because of this, the iterative nature of generative design can be time-consuming, requiring significant computational resources. Many attempts had to be made while working on this project, and often a single misclicked obstacle geometry can lead to hours of troubleshooting and inaccurate models. One could argue that with all the troubleshooting, it would be quicker to simply design the part yourself.
Another limitation is the dependency on advanced manufacturing methods such as powder bed fusion. While this type of manufacturing enables the production of intricate geometries, it can be cost-prohibitive for large-scale production due to high material and operational costs. Furthermore, the surface finish and dimensional accuracy of PBF components often require post-processing, adding to the production timeline. If a company wanted to produce thousands of a single component, this would be very difficult to do with SLS printing.
Despite these challenges, generative design excels in applications where lightweighting and part consolidation are critical. Aerospace and automotive industries, as demonstrated, benefit significantly from these capabilities. However, its utility diminishes in scenarios where traditional manufacturing methods suffice or where high-volume production is required.


## AlSi10Mg Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH286ddQT78850c0d8a4996eadfd3d622c95?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

## Nylon 12 Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH286ddQT78850c0d8a4a2e8659d0ad315d4?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

{% include gallery %}

