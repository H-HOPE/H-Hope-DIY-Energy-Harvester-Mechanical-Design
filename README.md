<div align="right">
<img src="/images/Logo_istituzionale.png" alt="drawing" width="250"/>
</div>

# H-HOPE DIY Energy Harvester

**This guide is Part I of a three-part H-HOPE DIY build series.** Part I shows how to build the mechanical H-HOPE DIY energy harvester (the ‘harvester’) (the frame, oscillating cylinder, springs, transmission, flywheel and mechanical coupling) as either a **standalone demonstrator** or as a **complete mechanical module ready to connect to the H-HOPE DIY generator**. It contains everything a builder, student, or maker needs to go from parts to a working mechanical harvester:

---

**[Part II - H-HOPE DIY Generator](https://github.com/H-HOPE/H-HOPE-H-Hope-energy-harvester-induction-generator-design)** - Instructions for building the H-HOPE DIY generator that converts the harvester’s rotary/mechanical output into electrical power

**[Part III - H-HOPE DIY Electronics](https://github.com/H-HOPE/H-Hope-energy-harvester-electronic-design)** - Power control electronics that convert the H-HOPE DIY generator’s AC output into a USB-compatible DC supply for charging phones and small devices.

---

## Table of Contents

- [Introduction and principle of operation](#introduction-and-principle-of-operation)
- [Materials & Tools](#materials--tools)
  - [Bill of Materials & Price Estimate](#bill-of-materials--price-estimate)
  - [Tools](#tools)
- [3D Printed Parts for the harvester](#3d-printed-parts-for-the-harvester)
- [Harvester Assembly](#harvester-assembly)
  - [Aluminium frame and preloading mechanism (D and C)](#aluminium-frame-and-preloading-mechanism-d-and-c)
  - [Cylinder assembly (A)](#cylinder-assembly-a)
  - [Flywheel assembly (G)](#flywheel-assembly-g)
  - [Spring and rod assembly (B, E)](#spring-and-rod-assembly-b-e)
  - [Shaft (I)](#shaft-i)
    - [Shaft assembly With DIY Generator](#shaft-assembly-with-diy-generator)
    - [Without DIY Generator](#without-diy-generator)
  - [Assembly of the cylinder, springs and vertical rod to the Harvester frame](#assembly-of-the-cylinder-springs-and-vertical-rod-to-the-harvester-frame)
  - [Test of the operation](#test-of-the-operation)
- [Water-channel measurement results](#water-channel-measurement-results)
  - [Measurement parameters](#measurement-parameters)
    - [Cylinder size](#cylinder-size)
    - [Water velocity](#water-velocity)
    - [Oscillation amplitude](#oscillation-amplitude)
  - [Measurements results](#measurements-results)
    - [Best-performing configuration](#best-performing-configuration)
    - [Cylinder size comparison](#cylinder-size-comparison)
    - [Effect of water velocity](#effect-of-water-velocity)
  - [Practical build recommendation](#practical-build-recommendation)

---

## Introduction and principle of operation

The **harvester**, visible in Figure 1 is a simple, modular, and accessible mechanical system to convert the kinetic energy of flowing water into rotational motion, which is then converted into electrical power through a generator.  

The design is primarily aimed at **hobbyists, students, and researchers**, using standard aluminium profiles, off-the-shelf mechanical components, and basic workshop tools. All plastic components can be easily 3D-printed, with their models included in this build guide, while all remaining harvester parts are available on AliExpress for convenient sourcing.
The design emphasizes ease of assembly, allowing users to construct a fully functional water energy harvesting system without specialized machinery. By following step-by-step assembly instructions and using off-the-shelf parts, anyone can replicate the harvester to generate electricity from flowing water such as a small stream, river, channel, making it a practical and educational DIY project for sustainable energy exploration. For optimal performance, a water velocity between 0.6 and 1.0 m/s is recommended.

<p align="center">
  <img src="images/Assembly/Harvester_1.jpg" alt="Left view" width="45%" />
  <img src="images/Assembly/Harvester_2.jpg" alt="Right view" width="45%" />
</p>
<p align="center">
<b>Fig. 1:</b> Assembled harvester.</p>


<p align="center">
  <img src="./images/Assembly/Harvester_parts.JPG" alt="H-HOPE harvester" width="100%" />
</p>

<p align="center"><b>Fig. 2:</b> View of the harvester model.</p>


The model of the harvester, visible in Figure 2 shows the mechanical structure of the harvester. The assembly consists of a modular aluminium frame supporting a horizontal oscillating cylinder, a flywheel, and vertical guide elements to transmit motion to a central shaft. In this configuration, the **cylinder (A)** is mounted horizontally and attached via **return springs (B)** to allow vertical oscillations while constraining horizontal movement. **Preloading mechanisms (C)** can adjust the spring tension to set the cylinder’s equilibrium position depending on its weight. **Vertical connecting rods (E)** with bearings transfer the oscillating motion of the cylinder to a **shaft (I)**,  which is supported by **bearings (H)**. This shaft is coupled to a **rotor (F)** and **flywheel (G)**, which help smooth the motion and can be linked to an induction generator. The **aluminium frame (D)** provides a modular and rigid support structure for the entire system. The pulley and cable arrangement visible in the image ensures the vertical movement of the cylinder is mechanically transmitted to the rotating shaft, which can then drive a generator rotor.

**Principle of Operation - Vortex-Induced Vibration (VIV)**

The vortex shedding process results in quasi-periodic pressure fluctuations around the cylinder. These alternating pressure differentials between the upper and lower surfaces generate an unsteady lift force, acting primarily in the transverse (vertical) direction. When the cylinder is mounted to permit vertical motion while restricting horizontal displacement, this oscillatory lift force induces vertical vibrations of the structure. The magnitude of the lift force is important for both performance and design of the VIV energy harvesters. For a given pressure differential, the lift force is proportional to the surface area exposed to the flow. Thus, increasing the cylinder diameter increases the area subject to pressure fluctuations, resulting in a higher lift force during vortex shedding. Where channel or stream dimensions allow, employing a cylinder with the maximum feasible height is advantageous, as it increases oscillation amplitude and improves the energy extraction potential and overall efficiency of the harvester.

Vertical harvester motion forms the basis for energy extraction in systems designed to harness vortex-induced vibrations (VIV), where mechanical oscillation energy is converted into usable electrical power. When the vortex shedding frequency approaches the natural frequency of the structure, resonance may occur, producing large-amplitude oscillations. Devices designed to extract energy from these oscillations are referred to as VIV energy harvesters, such as the system developed here. The harvester’s operating principle is based on Kármán vortex shedding coupled with large-amplitude oscillations of the energy harvester.

To harvest the lift force generated by the oscillating flow, the structure must allow large oscillatory displacements that can be sustained over time. Consequently, the natural (resonant) frequency of the harvester should be tuned to match, or lie very close to, the dominant vortex-shedding frequency of the flow, thereby maximising the energy captured per cycle.

---

## Materials & Tools

All the parts can be sourced from [AliExpress](https://www.aliexpress.com) using the links below. Some items (e.g., profiles or nuts) may also be available locally for faster delivery. Below is a complete list of all the components and hardware required for the build, including direct links and backup snapshots to AliExpress.

### Bill of Materials & Price Estimate

#### Frame
- 2x Bosch profile 500 mm ↘︎
- 2x Bosch profile 150 mm → [AliExpress items](https://www.aliexpress.com/item/1005002652962344.html) [Page screenshot](./images/1_profiles.PNG)
- 2x Bosch profile 300 mm ↗
- 20× Corner Bracket – joins → [AliExpress item](https://www.aliexpress.com/item/1005008248063572.html) [Page screenshot](./images/2_brackets.PNG)

#### Bearings
- 2× 10×26×8 mm (6000 OPEN) → [AliExpress item](https://www.aliexpress.com/item/1000006697893.html) [Page screenshot](./images/3_bearings_big.PNG)
  *(Open type has slightly less friction than closed)*  
- 2× 3×10×4 mm → [AliExpress item](https://www.aliexpress.com/item/1005007624995531.html) [Page screenshot](./images/3_bearings_small.PNG)

#### Flange
- 2× 10 mm inner diameter → [AliExpress item](https://www.aliexpress.com/item/1005006166768847.html) [Page screenshot](./images/4_flange.PNG)

#### Weights
- 4× (8×) 100 g weights → [AliExpress item](https://www.aliexpress.com/item/1005009254304005.html) [Page screenshot](./images/5_weights.PNG)

#### Inserts
- 50× M3 inserts (OD 4.5 mm, length 8 mm) → [AliExpress item](https://www.aliexpress.com/item/1005009169647177.html) [Page screenshot](./images/6_inserts.PNG)

#### Threaded Rod
- 1× M6, 500 mm → [AliExpress item](https://www.aliexpress.com/item/1005010030305641.html) [Page screenshot](./images/7_threaded_rod.PNG)

#### Shaft
- 1× 300 mm, Ø10 mm rod → [AliExpress item](https://www.aliexpress.com/item/1005007648254828.html) [Page screenshot](./images/12_main_rod.PNG)

#### Spacers
- 10× OD8 × M6 spacers, length 8 mm → [AliExpress item](https://www.aliexpress.com/item/1005009939446609.html) [Page screenshot](./images/8_spacer.PNG)

#### Stainless Steel Round Rod
- 4× 300 mm, Ø3 mm rods → [AliExpress item](https://www.aliexpress.com/item/1005006331386855.html) [Page screenshot](./images/9_round_rod.PNG)

#### Bolts, Nuts & Washers
- 10pcs M3 bolts, 12 mm in lenght → [AliExpress item](https://www.aliexpress.com/item/4001072025844.html) [Page screenshot](./images/10__M3_screws.PNG)

- 6pcs M6 nuts → [AliExpress item](https://www.aliexpress.com/item/1005006982532067.html) [Page screenshot](./images/11_M6_nuts.PNG)

- 4PCS M5 nuts and bolts 25 mm in lenght (for mounting the generator)
  
**Total Estimated Cost for the material (2025)** *(Generator and electronics not included)*

**≈ 95 €**

---

### Tools
- Screwdrivers, wrenches
- Drill/driver, bench vise
- Metal saw
- Vice
- 3D printer
- Safety gear (gloves, goggles)
- Quick glue
- Soldering iron (for inserting inserts)

---
## 3D Printed Parts for the harvester

A total of 17 parts need to be 3D-printed to complete the harvester assembly. All parts are available in both STL and STEP formats and can be downloaded here: [3D printed harvester parts](./3D%20parts). For added protection against moisture or water exposure, you can optionally coat the printed parts with a plastic spray sealant. The printing process of the parts is visible in Figure 3.


<p align="center">
  <img src="./images/Assembly/Harvester_printing.jpg" alt="H-HOPE harvester" width="50%" />
</p>

<p align="center"><b>Fig. 3:</b> Printing the 3D parts for the harvester.</p>

---

## Harvester Assembly

 - The **harvester** may be assembled either **with the H-HOPE DIY generator** attached, as visible in Figure 4 left **or as a standalone mechanical module**, as visible in Figure 4 right. When built without the generator the unit can function as a mechanical demonstrator and can be left ready for later coupling to a third-party generator.

 - Build instructions and parts lists for both configurations (Mechanical only and Mechanical and Generator) are provided below so the builder can choose the configuration that best fits their goals.


<p align="center">
  <img src="images/Assembly/Harvester_with_generator.png" alt="Left view" width="45%" />
  <img src="images/Assembly/Harvester_without_generator.png" alt="Right view" width="45%" />
</p>
<p align="center">
<b>Fig. 4:</b>Harvester assembly with (left) and without (right) the H-HOPE DIY generator.
</p>

Figure 4 shows a model view of the harvester, with (left) and without (right) the H-HOPE DIY generator, displaying its individual mechanical components and how they are assembled.

The assembly process, regardless of the generator installation, is identical up to the "Shaft" section. This section is divided into two parts, allowing the user to follow the procedure either with or without the generator assembly.

### Aluminium frame and preloading mechanism (D and C)

The assembly of the harvester begins with the assembly of the aluminium frame (D) and preloading mechanism (C).

<p align="center">
  <img src="images/Assembly/Frame_1.jpg" alt="Right view" width="55%" />
</p>
<p align="center">
<b>Fig. 5:</b> Harvester frame and preloading mechanism assembly parts.
</p>

First assemble the **horizontal part of the aluminium frame (D)** with corner brackets and M6 fasteners. Place two 500 mm, 20x20 mm Aluminium profiles in parallel. Add two 150 mm profiles at each end, to connect the 500mm profiles together. Assemble the profiles together with joints at each of the 4 corners, as visible in the animation on the right side of Figure 6. The finished harvester horizontal profile is visible in Figure 7.

<p align="center">
  <img src="images/Assembly/Frame_2.jpg" alt="Right view" width="55%" />
  <img src="images/GIF/Frame_1.gif" alt="Left view" width="30%" />
</p>
<p align="center">
<b>Fig. 6:</b> Harvester horizontal frame assembly parts (left) and animation of harvester horizontal frame assembly (right).
</p>

<p align="center">
  <img src="images/Assembly/Frame_3.jpg" alt="Right view" width="55%" />
</p>
<p align="center">
<b>Fig. 7:</b> Completed harvester horizontal frame assembly.
</p>

**Assembly of the harvester vertical aluminium frame and preloading mechanism**.

First, install the preloading mechanism components (shown in Figure 8 and in the animation in Figure 9) onto the vertical 300 mm, 20x20 mm aluminium profiles. The required length of the four M5 bolts is 23 mm, however, in this assembly, 25 mm bolts were used along with two additional washers to achieve the correct overall length.

<p align="center">
  <img src="images/Assembly/Frame_4.jpg" alt="Right view" width="45%" />
  <img src="images/Assembly/Frame_5.jpg" alt="Left view" width="45%" />
</p>
<p align="center">
<b>Fig. 8:</b> Harvester preloading mechanism parts (left) and finished assembly of the preloading mechanism (right).
</p>

<p align="center">
  <img src="images/GIF/Verical_frame_assembly.gif" alt="Left view" width="65%" />
</p>
<p align="center">
<b>Fig. 9:</b> Animation of harvester horizontal frame and preloading mechanism assembly.
</p>

Place each 300 mm profile vertically and secure it with three joints to the harvester horizontal profile, one at the bottom, one on the left side, and one on the right side, then repeat the same process on the opposite side of the frame, ensure that each profile extends 8 mm above the top of the frame and that the bottom part of the preloading mechanism is positioned 15 mm from the lower end of the vertical profile, as illustrated in the left side of the Figure 11. Ensure **profile alignment** to minimize bearing wear and losses.

Before connecting vertical profiles to the horizontal aluminium frame, sand off the excessive aluminium pins (if they exist) in corner joints to make a good connection, as visible in Figure 10 (left and right).

<p align="center">
  <img src="images/Assembly/Frame_6.jpg" alt="Right view" width="45%" />
  <img src="images/Assembly/Frame_8.jpg" alt="Left view" width="45%" />
</p>
<p align="center">
<b>Fig. 10:</b> Sanded pins on aluminium joints.
</p>

<p align="center">
  <img src="images/Assembly/Frame_distances_1.png" alt="Right view" width="25%" />
  <img src="images/Assembly/Frame_distances_2.png" alt="Left view" width="65%" />
</p>
<p align="center">
<b>Fig. 11:</b> Mounting offset of the preloading mechanism, vertical profiles (left) and offset of the items installed on the horizontal frame (right).
</p>


The finished frame assembly is shown in Figure 12.

<p align="center">
  <img src="./images/Assembly/Frame_7.jpg" alt="H-HOPE harvester" width="60%" />
</p>

<p align="center"><b>Fig. 12:</b> Assembled harvester aluminium frame.</p>


---

### Cylinder assembly (A)

We continue with the harvester cylinder assembly (A).

In the left side of Figure 13 we can see the parts needed to assemble the harvester cylinder. We can see that the cylinder is 3D printed and is made from two parts. At each end of the cylinder there is a larger disc, that improves the harvester efficiency. The cylinder has a 6 mm hole running through its entire length. On the right side, there are six M6 nuts and two 6x8 mm spacers, below is a 500 mm M6 threaded rod.

<p align="center">
  <img src="images/Assembly/Cylinder_1.jpg" alt="Left view" width="45%" />
  <img src="images/Assembly/Cylinder_2.jpg" alt="Right view" width="45%" />
</p>
<p align="center">
<b>Fig. 13:</b> Cylinder assembly parts (left) and rod cutting (right).
</p>

<p align="center">
  <img src="./images/GIF/Gif_cylinder.gif" alt="H-HOPE harvester" width="50%" />
</p>
<p align="center"><b>Fig. 14:</b> Animation of harvester cylinder assembly.</p>

The first step is to shorten the M6 rod by 165 mm to 335 mm, as visible in Figure 13 (right). After that, assemble the cylinder and install the threaded rod through the cylinder hole. At each end of the rod add two M6 nuts and lightly tighten them. To each side add a spacer and additional 2 M6 nuts, as visible in the animation on Figure 14 and Figure 15.

<p align="center">
  <img src="images/Assembly/Cylinder_3.jpg" alt="Left view" width="45%" />
  <img src="images/Assembly/Cylinder_4.jpg" alt="Right view" width="45%" />
</p>
<p align="center">
<b>Fig. 15:</b> Installed nuts and spacer, left and assembled cylinder, visible on the right.
</p>


### Flywheel assembly (G)

The next step is to assemble the harvester flywheel (G).

<p align="center">
  <img src="./images/Assembly/Flywheel_1.jpg" alt="H-HOPE harvester" width="80%" />
</p>

<p align="center"><b>Fig. 16:</b> Flywheel assembly parts.</p>

<p align="center">
  <img src="./images/GIF/Gif_flywheel.gif" alt="H-HOPE harvester" width="70%" />
</p>
<p align="center"><b>Fig. 17:</b> Animation of harvester flywheel assembly</p>


With the help of a soldering iron insert four M3 inserts into the holes in the back side of the flywheel, as visible in Figure 18.

<p align="center">
  <img src="images/Assembly/Flywheel_3.jpg" alt="Left view" width="45%" />
  <img src="images/Assembly/Flywheel_4.jpg" alt="Right view" width="45%" />
</p>
<p align="center">
<b>Fig. 18:</b> Installing the M3 inserts with a soldering iron on the back side of a flywheel.
</p>

Install two inserts in the front end of a flywheel into the third hole, closest to the center, as visible in Figure 19.

<p align="center">
  <img src="images/Assembly/Flywheel_5.jpg" alt="Left view" width="45%" />
  <img src="images/Assembly/Flywheel_6.jpg" alt="Right view" width="45%" />
</p>
<p align="center">
<b>Fig. 19:</b> Installing the M3 insert with a soldering iron on the front side of a flywheel.
</p>

 Use M3 20 mm in length bolts, to fix the flange to the back side of a flywheel. The flange must be positioned as visible in Figure 20.

<p align="center">
  <img src="images/Assembly/Flywheel_7.jpg" alt="Left view" width="45%" />
</p>
<p align="center">
<b>Fig. 20:</b> Installing the flange on the flywheel. 
</p>

Add two 100 g weights in opposite holes into each flywheel, as visible in the right side of a Figure 21.

<p align="center">
  <img src="images/Assembly/Flywheel_8.jpg" alt="Left view" width="45%" />
  <img src="images/Assembly/Flywheel_9.jpg" alt="Right view" width="45%" />
</p>
<p align="center">
<b>Fig. 21:</b> Flywheel with installed flanges on left and weights on the right.
</p>


### Spring and rod assembly  (B, E)

The harvester return spring (B) and vertical rod (E) are made from 3 mm stainless steel rod, two bearings, six printed parts and four spacers, as visible in Figure 22. The animation on how to assemble the vertical rod is visible in Figure 23.

<p align="center">
  <img src="./images/Assembly/Rod_spring_1.jpg" alt="H-HOPE harvester" width="40%" />
</p>
<p align="center"><b>Fig. 22:</b> Parts required for assembly of the harvester return spring and vertical rod.</p>

<p align="center">
  <img src="./images/GIF/GIF_vertical_rod_spring.gif" alt="H-HOPE harvester" width="60%" />
</p>
<p align="center"><b>Fig. 23:</b> Animation of the harvester vertical rod assembly.</p>

First, cut two of the 300 mm rods down by 35 mm to 265 mm; these will be used as the harvester’s vertical rods. Leave the other two rods at their full 300 mm length for the return spring.

Insert the two 3x10x4 mm bearings into the openings of the two 3D-printed end caps, as visible in the lower-left side of Figure 24. Insert the four spacers into the holes of the 3D-printed end caps, as shown on the upper-left side of Figure 24. Then attach the 3D-printed end caps to the ends of the vertical rods (E), and fit only two onto the return spring (B), as shown on the right side of Figure 24. It is recommended to apply a small amount of quick glue into the hole just before inserting the 3D printed plastic end caps to improve bonding.

<p align="center">
  <img src="images/Assembly/Rod_spring_2.jpg" alt="Left view" width="45%" />
  <img src="images/Assembly/Rod_spring_3.jpg" alt="Right view" width="45%" />
</p>
<p align="center">
<b>Fig. 24:</b> 3D printed plastic endings with inserted bearings and spacers (left) and assembled return springs and vertical rods (right).
</p>


### Shaft (I)

The harvester shaft (I) carries both flywheels and, in the “with‑generator” configuration, the H‑HOPE DIY generator rotor. It converts the vertical oscillation of the cylinder into rotary motion and, when the generator is installed, also provides the mechanical input to the electrical part of the system.

The shaft assembly is based on a 300 mm long, Ø10 mm steel rod, two 6000‑type bearings, two 3D‑printed bearing holders, two flywheels (G) and, optionally, the H‑HOPE DIY generator rotor and stator. All the parts, needed for shaft assembly are visible in Figure 25.

#### Shaft assembly With DIY Generator
<p align="center">
  <img src="./images/Assembly/Main_shaft_1.jpg" alt="H-HOPE harvester" width="70%" />
</p>
<p align="center"><b>Fig. 25:</b> Parts required for assembly of the harvester shaft - with H-HOPE DIY generator.</p>


<p align="center">
  <img src="./images/GIF/GIF_generator_main_rod.gif" alt="H-HOPE harvester" width="70%" />
</p>
<p align="center"><b>Fig. 26:</b> Animation of the main shaft assembly with integrated H‑HOPE DIY generator.</p>

First, press one 10×26×8 mm bearing into each 3D‑printed bearing holder (Figure 27, left). Make sure the bearings are fully seated and square to the plastic surface.

<p align="center">
  <img src="images/Assembly/Main_shaft_2.jpg" alt="Left view" width="57%" />
  <img src="images/Assembly/Main_shaft_3.jpg" alt="Right view" width="32%" />
</p>
<p align="center">
<b>Fig. 27:</b> 3D‑printed bearing holders with bearings inserted (left) and generator stator mounted to the larger bearing holder (right).
</p>

Next, prepare the bearing holder that will carry the generator stator.

Insert four M5 nuts into the hexagonal pockets of the larger bearing holder. Place the generator stator so that the phase output block points outward and the coil side faces the future rotor position. Fix the stator to the bearing holder using four M5 bolts, as shown in Figures 27 (right) and 28 (left). Tighten the bolts evenly so that the stator sits flat on the mounting surface.

<p align="center">
  <img src="images/Assembly/Main_shaft_4.jpg" alt="Left view" width="45%" />
  <img src="images/Assembly/Main_shaft_5.jpg" alt="Right view" width="45%" />
</p>
<p align="center">
<b>Fig. 28:</b> DIY H-HOPE generator stator attached to the bearing holder, image from front side (left), DIY H-HOPE generator rotor attached to the flange (right).
</p>

Prepare the generator rotor as follows: Mount the aluminium shaft flange to the centre of the rotor disc using three M3 bolts (Figure 28, right). Ensure that the flange is centred and that the bolts are securely tightened. If not already done in Part II of the guide, glue the magnets into the circular pockets of the rotor disc, alternating polarity as required by the generator design.

<p align="center">
  <img src="images/Assembly/Main_shaft_6.jpg" alt="Left view" width="45%" />
  <img src="images/Assembly/Main_shaft_7.jpg" alt="Right view" width="45%" />
</p>
<p align="center">
<b>Fig. 29:</b> Completed rotor with glued magnets (left) and overview of the assembled generator components, flywheels, one bearing block and shaft (right).
</p>

Now you can assemble the shaft. Slide the generator rotor (with flange and magnets) onto the 10 mm shaft and tighten the flange clamping bolts so the rotor is roughly centred along the rod. Slide the stator–bearing‑holder assembly onto the shaft from the opposite side. At this stage the stator is not yet fixed to the frame, so you can freely adjust the air‑gap between rotor and stator (typically 4-6 mm). Add the second bearing holder onto the shaft on the other side of the rotor. Finally, mount one flywheel onto each end of the shaft and tighten their hub bolts against the shaft flat (or directly onto the shaft if no flat is present).

<p align="center">
  <img src="images/Assembly/Main_shaft_8.jpg" alt="Left view" width="65%" />
</p>
<p align="center">
<b>Fig. 30:</b> Fully assembled main shaft with flywheels at both ends, rotor fixed to the shaft and stator attached to its bearing holder.
</p>

At this point the complete “shaft module” is assembled, but not yet installed on the aluminium frame. Before mounting it, check that the shaft can be rotated by hand and that both bearings run smoothly.  

Figure 31 shows the finished shaft module (left) and an example of its final position in the frame (right). In the right photo a tape measure can be used to set the horizontal position of the bearing holder from the start of the aluminium profile. 

<p align="center">
  <img src="images/Assembly/Main_shaft_9.jpg" alt="Left view" width="45%" />
  <img src="images/Assembly/Main_shaft_10.jpg" alt="Right view" width="45%" />
</p>
<p align="center">
<b>Fig. 31:</b> Completed shaft assembly, ready for mounting on the harvester (left) and example of the recommended horizontal positioning of the bearing housing on the horizontal aluminium frame (right).
</p>

To install the shaft assembly into the harvester frame place the frame on a flat surface and attach the smaller bearing housing to one horizontal aluminium profile and the stator bearing housing to the opposite horizontal profile using T‑nuts and M5/M6 bolts, as shown in Fig. 31 (right). Adjust the position of both bearing holders using a ruler or tape measure so they are at the same distance from the edge of the horizontal frame. Lightly tighten the bolts, rotate the shaft and fine‑tune the position of both bearing blocks until the shaft spins freely without binding, then fully tighten the bolts.

#### Without DIY Generator

The assembly process is the same, simply omit mounting the H-HOPE generator stator to the 3D-printed bearing and generator holder, and do not mount the generator rotor on the rod.


### Assembly of the cylinder, springs and vertical rod to the Harvester frame.

In this step the three main mechanical sub‑assemblies are connected:
- the **oscillating cylinder** with its threaded M6 rod,
- the **return springs and vertical rods**, and
- the **shaft module** with flywheels and (optionally) generator.

<p align="center">
  <img src="images/Assembly/Assembly_1.jpg" alt="Left view" width="45%" />
  <img src="images/Assembly/Assembly_2.jpg" alt="Right view" width="45%" />
</p>
<p align="center">
<b>Fig. 32:</b> Cylinder, spring–rod assemblies and shaft module before installation (left) and attachment of the springs to the pre‑loading mechanisms (right).
</p>

**Attach the springs to the frame.**
Hook one end of each spring onto the upper hook of the pre‑loading mechanism on both sides of the frame (Figure 32, right). Leave the lower ends of the springs free for now; they will later connect to the cylinder.

**Install the cylinder between the springs.**
Place the cylinder in the centre of the frame, with the M6 threaded rod running horizontally. Attach the lower spring hooks to the 3D‑printed eyelets on the cylinder ends. At this stage the cylinder should be suspended by the two springs and able to move vertically with very little friction.

<p align="center">
  <img src="images/Assembly/Assembly_3.jpg" alt="Left view" width="45%" />
  <img src="images/Assembly/Assembly_4.jpg" alt="Right view" width="45%" />
</p>
<p align="center">
<b>Fig. 33:</b> Connection of the vertical rods to the cylinder (left) and hardware required to fix the upper ends of the rods to the flywheels (right).
</p>

**Connect the vertical rods to the cylinder.**
- Slide the lower bearings of the vertical rods onto the protruding M6 threaded rod on each side of the cylinder.
- Fix them in place using M6 nuts and, if required, spacers so that the rods remain vertical and parallel to the frame (Figure 33, left).
- Check that the rods can pivot freely on their bearings without binding.

**Adjust spring pre‑load.**
Rotate the pre‑loading bolts to set the desired spring tension. The cylinder should rest approximately in the middle of its travel when the springs are unloaded (no water flow). You can fine‑tune this later during testing.

**Connect the vertical rods to the flywheels.**
- Rotate the shaft so that the attachment holes in both flywheels are aligned and approximately above the vertical rods.
- Using the hardware shown in Figure 33 (right), bolt the upper bearings of the vertical rods to the flywheel connection points. Make sure that both rods are attached at the same radius from the shaft centre to guarantee symmetric motion.

<p align="center">
  <img src="images/Assembly/Assembly_5.jpg" alt="Left view" width="45%" />

</p>
<p align="center">
<b>Fig. 34:</b> Bolt and spacer view, before connecting the vertical rod to the flywheel. The same procedure is repeated on the opposite side.
</p>

Once both rods are connected, slowly move the cylinder up and down by hand. The flywheels should start to rotate smoothly and the cylinder should return to its equilibrium position when released. If you notice any sticking or misalignment:

- Check that the vertical rods are straight and parallel.
- Verify that the spring forces are balanced left/right.
- Loosen the bearing block bolts slightly and re‑align the shaft until the rotation is smooth.

When these checks are complete, the full mechanical harvester assembly is finished and you can proceed to the Test of the operation section.


### Test of the operation

The H-HOPE energy harvester was tested in a water channel at a constant flow velocity of 0.9 m/s. The water depth during the test was 25 cm. Figures 35 and 36 show the harvester in operation. A video of the harvester with the  [DIY H-HOPE generator](https://github.com/H-HOPE/H-HOPE-H-Hope-energy-harvester-induction-generator-design) and [power electronics](https://github.com/H-HOPE/H-Hope-energy-harvester-electronic-design) is also available on YouTube [here](https://youtu.be/Jox99EthLKE).

<p align="center">
  <img src="./images/GIF/Harvester_test_gif_1.gif" alt="H-HOPE harvester" width="70%" />
</p>
<p align="center"><b>Fig. 35:</b> Animation of the H-HOPE energy harvester in operation during water-channel testing at a flow velocity of 0.9 m/s (water depth 25 cm).</p>


<p align="center">
  <img src="images/Assembly/Harvester_test_2.jpg" alt="Left view" width="45%" />
  <img src="images/Assembly/Harvester_test_3.jpg" alt="Right view" width="45%" />
</p>
<p align="center">
<b>Fig. 36:</b> H-HOPE energy harvester in operation during water-channel testing at a flow velocity of 0.9 m/s (water depth 25 cm).
</p>


## Water-channel measurement results

To evaluate the performance of the energy harvester, a series of experimental tests was carried out with different combinations of test parameters. The main test parameters were the cylinder diameter, water velocity, and oscillation amplitude. These parameters were varied to investigate their influence on the oscillatory response of the cylinder and the resulting mechanical power transfer to the generator.

Three cylinder sizes were tested under different flow conditions and prescribed oscillation amplitudes. For each test configuration, the oscillation frequency and generator torque were measured while the electrical load was gradually increased. This testing procedure allowed us to evaluate how individual parameters affect the operation and performance of the energy harvester.

A sample video of the test measurements is available here: https://youtu.be/U6G2Xj3FoK8

### Measurement parameters

#### Cylinder size

Three 3D-printed cylinders (A), with diameters of 50 (blue), 60 (black), and 70 mm (red), as shown in Figure 37, were tested. All cylinders had a length of 0.25 m. The relative density and mass of each cylinder can be seen in the table below.

| Cylinder diameter | Relative density | Mass |
|---:|---:|---:|
| 50 mm | 0.690 | 0.366 kg |
| 60 mm | 0.524 | 0.400 kg |
| 70 mm | 0.446 | 0.463 kg |

<p align="center">
  <img src="./images/Assembly/Tested_cylinders.jpg" alt="H-HOPE harvester" width="70%" />
</p>
<p align="center"><b>Fig. 37: </b>3D-printed cylinders, with diameters of 50 (blue), 60 (black), and 70 mm (red)</p>

The return springs (B) were made from 3 mm stainless-steel rod and had a free length of 350 mm. The water channel was 500 mm wide and 500 mm high, as visible in Figure 35 and 36. 

#### Water velocity

The following combinations of water velocity and water depth in the water channel were tested:

| Water velocity | Water depth |
|---:|---:|
| 0.70 m/s | 210 mm |
| 0.80 m/s | 210 mm |
| 0.90 m/s | 210 mm |
| 1.10 m/s | 180 mm |
| 1.20 m/s | 200 mm |

#### Oscilation amplitude

Cylinder displacement is expressed as **oscillation amplitude**. The oscillation amplitude is set by the position where the vertical connecting rod (E) is attached to the flywheel (G) as visible in Figure 19. Moving the attachment point closer to or further from the shaft (I) changes the vertical travel of the cylinder. Therefore, the amplitude is a fixed mechanical setting for each test and does not change freely with water velocity.

Oscillation amplitudes of 20, 30 and 40 mm were tested (Figure 38). During each test, the oscillation frequency and torque on the generator stator were measured at different electrical loads. The electrical load was increased until the maximum torque at which the cylinder could still oscillate.


<p align="center">
  <img src="./images/Assembly/Mouting_points.jpg" alt="H-HOPE harvester" width="70%" />
</p>
<p align="center"><b>Fig. 38: </b>Mouting points for oscillation amplitudes of 20, 30 and 40 mm are indicated by black arrows.</p>

### Measurements results

#### Best-performing configuration

The **60 mm cylinder gave the best overall results** during the water-channel measurements.

**The highest measured efficiency was obtained with the 60 mm cylinder at a water velocity of 0.80 m/s and an oscillation amplitude of 30 or 40 mm. The efficiency was slightly above 8.5%**.

When the results from the different amplitudes were compared, the 60 mm cylinder also had the highest average oscillation frequency, generated power and efficiency.

The difference of power output and efficiency between the **30 and 40 mm** amplitudes was relatively small. For general operation, an oscillation amplitude between 30 and 40 mm is recommended.

If the primary objective is to maximize generated power rather than efficiency, the highest measured value was achieved at a water velocity of 1.20 m/s using the 60 mm cylinder and an amplitude of 40 mm, resulting in a generated power of **0.46 W**. Although the higher water velocity increased the power output, the corresponding efficiency was lower than that obtained at a water velocity of 0.80 m/s. The table below summarizes the recommended configurations for the two main design objectives.

| Design objective | Recommended configuration | Result |
|---|---|---|
| Highest efficiency | 60 mm cylinder diameter, 30-40 mm oscilation amplitude, 0.80 m/s water velocity | efficiency around 8.5% |
| Highest power output | 60 mm cylinder diameter, 40 mm oscilation amplitude, 1.20 m/s water velocity | Power output of 0.46 W |


#### Cylinder size comparison

The table below summarizes the performance of the three tested cylinder diameters. The comparison shows that the 60 mm cylinder provided the best overall performance, while the 50 mm and 70 mm cylinders produced lower average power and efficiency under the tested conditions.

| Cylinder | Performance Assessment |
|---|---|
| **50 mm** | The 50 mm cylinder produced moderate power and efficiency. Its highest efficiency was measured at 0.80 m/s water velocity, while the generated power at 1.20 m/s water velocity. Overall, its average performance was lower than that of the 60 mm cylinder. |
| **60 mm** | The 60 mm cylinder gave the best overall results. It had the highest average oscillation frequency, power and efficiency. The highest efficiency was measured at 0.80 m/s water velocity with a 30-40 mm amplitude, while the highest power was measured at 1.20 m/s water velocity. |
| **70 mm** | The 70 mm cylinder had a lower average oscillation frequency and efficiency than the 60 mm cylinder. Its highest efficiency was measured at 0.90 m/s water velocity. Continuous oscillation could not be maintained at some operating points. |

The measurements show that increasing the cylinder diameter does not automatically improve H-HOPE harvester performance.

A larger cylinder is exposed to a larger hydrodynamic force, but the final oscillation also depends on cylinder mass, natural frequency, spring stiffness, mechanical tuning and generator load. For the tested H-HOPE harvester configuration, **the 60 mm** cylinder provided the best power and efficiency results.


#### Effect of water velocity

Water velocity had a strong influence on the operation of the H-HOPE harvester.

At a water velocity below 0.70 m/s, the oscillation frequency and generated power were generally the lowest, which can be attributed to the lower kinetic energy available from the water flow. At water velocity of 0.80 m/s, the 50 and 60 mm cylinders achieved their highest efficiencies, indicating favorable conditions for converting the vortex-induced oscillations into electrical power. Results indicate that water velocities between 0.80 and 0.90 m/s provided the most favorable conditions for the H-HOPE harvester operation. At water velocity of 1.10 m/s, the oscillation frequency, generated power, and efficiency decreased for all three cylinders, suggesting a less favorable operating point for the H-HOPE harvester. At water velocity of 1.20 m/s, the oscillation frequency and generated power increased again, resulting in the highest absolute power output measured during the measurements; however, the efficiency remained lower than at water velocity of 0.80 m/s. 

Overall, the results show that increasing water velocity does not necessarily lead to higher efficiency of the H-HOPE harvester, as its performance also depends on the interaction between the vortex-shedding frequency and the dynamic characteristics of the system.

The measurements show that **water velocity has a larger effect on oscillation frequency, generated power and efficiency than the selected oscillation amplitude**.

### Practical build recommendation

Based on the water-channel measurements, the following configuration is recommended for H-HOPE harvester operation:

- use a **60 mm diameter cylinder**;
- use an **oscillation amplitude between 30 and 40 mm**; and
- aim for a water velocity of approximately **0.80 m/s**.

This configuration gave the best combination of efficiency and stable operation during testing.

If the main goal is to obtain the highest possible generated power, a water velocity of **1.20 m/s** can be used. The generated power is higher at this water velocity, but the efficiency is lower.

---

<div align="center">
<img src="./images/H-HOPE_footer.JPG" alt="drawing" width="1472"/>
</div>
