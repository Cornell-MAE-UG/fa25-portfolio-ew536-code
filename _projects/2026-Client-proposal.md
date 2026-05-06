---
layout: project
title: MAE 2250 SLF Removal Apparatus
description: Pre-Harvesting Apparatus
technologies: [CAD, Vertical Bandsaw, Drill, Saw, 3D Printing]
image:
---

## Table of Contents
- [Client Pitch](#client-pitch)
- [Functional Prototype](#functional-prototype)
- [Client Report](#client-report)

---
Spotted lanternflies (SLF) infest grapevines, contaminating harvests and damaging vineyards that are critical to local economies in regions such as New York. Within this broader challenge, this work targets the specific, high-impact sub-problem of removal of SLF immediately prior to harvest, when insects attached to vines are likely to be collected with grape clusters and directly contaminate the product. This focus enables large short-term gains without requiring full population control.
At harvest, grapes are extremely delicate and easily damaged or dislodged, while SLF exhibit strong adhesion to surfaces, requiring substantial but carefully controlled force for removal. With chemical and biological methods still uncertain and difficult to scale, a kinetic alternative is necessary. The proposed solution integrates directly with existing harvesting equipment, avoids disruption to workflows or costly vineyard-wide deployment, scales easily, and targets the SLF population most immediately affecting yield. 

---

## Client Pitch
**Team:** The Entomophiles
**Client(s):** Cornell CALS Extension/E&J Gallo Winery/National Grape  
 
## Problem statement 
Spotted lanternflies (SLF) infest grapevines, contaminating harvests. We aim to remove ~90% before harvest. Because grapes are fragile and SLF adhere strongly, removal requires substantial but carefully controlled force.


## Impact
This product will allow grape farmers to solve the issue of SLF within harvested crops, allowing for more loads to be accepted alongside large-scale removal operations.  

---

## Proposed direction(s): Pre-Harvest Processing


**What it is:** An apparatus that is mounted to the front of a harvester and removes the SLF before the harvesting begins. We will use water or air, and either flood or direct the fluid towards SLF.
 

**How it would be used:**


- Device mounts to the harvester and connects to water, air, and/or power.
- Apparatus dislodges SLF from vines immediately prior to harvest.
 

**Why it’s better than the status quo:**


- Addresses problem in short term regarding yield
- More adaptable to existing infrastructure  


**End-of-semester proof-of-concept:** A battery-powered miniature prototype will use air and/or water (directed or undirected) to remove simulated SLF (miniature suction cups) from a simulated or real grape vine, supplied by a water tank.

---

## Key risks/unknowns

- SLF removal may dislodge grapes or damage vines, reducing yield and future harvests; this can be tested using simulated SLF on real vines with fruit.
- Fluid use may oversaturate soil or contaminate crops; non-water chemicals could affect grape quality or food safety. We would use soil-safe fluids and minimize volume.

---

## Questions for the client


1. **How much water / air pressure is necessary to wash off SLF?**  

   *Decision affected:* Determination of optimal force to apply. 
   


2. **What are the dimensions and physical limitations of the harvester?**  

   *Decision affected:* Determination of apparatus size, fluid output, system complexity.



3. **Is a stable water supply available, and can the harvester power a compressor?**  

   *Decision affected:* If not, air requires onboard compression and water requires onboard storage, increasing weight.



## Functional Prototype

### Design Sketch
![Design Sketch]({{ "/assets/images/2250drawing.png" | relative_url }}){: .setup-image style="width: 500px"}

### Component List
![Component List]({{ "/assets/images/2250list.png" | relative_url }}){: .setup-image style="width: 500px"}


### Assembly Instructions

1. Assemble main frame  
   a. Fit metal rods into printed corner joints tightly. Orient 4 shorter rods vertically for balanced structure.  

2. Assemble pipe structure  
   a. Connect four T-connectors(horizontally) in a straight line with 1¾” pieces in between each connector and 1¾” pieces at the ends as well. Place an end cap on one end.  
   b. On each T- connector, connect the foot-long pvc pipes, with drilled holes alternating in offset. Place end caps at the end of each pipe.  
   c. Hose - Used 1” schedule 40 PVC to connect threaded barbed hose connectors to the ¾” PVC. We plan on using the other side of the hose to connect to our reservoir with a valve in the future. The hose was attached between these barbed connectors  
   d. Attach pipe structure to frame with zip-ties (temporary). Where necessary, tie two zip-ties together for increased length.  

---

### Design Test

Poured water into the hose of the prototype several times. Placed structure above two bins to collect water.  

- Visually inspected for unintended water leakages.  
- Part it’s testing: Testing security of connections, whether significant design changes are necessary for the parts conducting water.  
- Results: Noticed small dripping leakage at threaded connection between PVC pipe and barbed hose connector  
- Conclusion: Tapping the PVC pipe at the connection could reduce leakage.  

- Placed absorbent cloth in the bin under the prototype.  
- Part it’s testing: Whether the “checkerboard” distribution of holes and pipes is sufficient to ensure good saturation of the area within the frame.  
- Results: Cloth was fully soaked.  
- Conclusion: Good saturation is achieved. However, it may be a future consideration to implement nozzles or other to further improve saturated area and reduce damage to plants caused by a direct dripping flow.  

- Measured 1000mL of water, poured into the hose at a steady rate. Time to fully drain was recorded.  
- Part it’s testing: Hose and piping carrying water, and whether there are significant blockages.  
- Results: Expended 1000mL in 58.07 sec.  
- Conclusion: Water flows well. Existing connections and methods of processing piping are good in this regard.  

---

### Success Criteria

- 16 mL/sec water flow rate- expends the small scale jug in about 4 minutes. Sufficient water flow is important to knock SLF off, but excessive flow is harmful (can wash away grapes).  
- Goal achieved: Expends 1000mL in 58.07 sec, which is a flow rate of 17.2 mL/sec. Therefore, we know water flows efficiently through the piping. However, we believe that with improved nozzles, we can retain full saturation with less flow, thus increasing efficiency with respect to the amount of water consumed.  

- Minimal frame deflection when only supported from one end. A sturdy, stable structure is necessary for repeated use.  
- Goal achieved: Frame is sturdy and stands stable on the edges of a plastic bin.  

- Open center for grape vines to pass through, and water saturates at least 75% of the surface area directly below the frame (0.75 square feet) within 30 seconds. Water should be spread around evenly within the frame such that no areas potentially containing SLF are missed.  
- Goal achieved: Placed absorbent cloth in bin under the prototype to test the surface area that the water reaches; cloth was fully soaked.



## Client Report

### Final Prototype 
![Photo of final prototype and mockup]({{ "/assets/images/IMG_8823.jpg" | relative_url }}){: .setup-image style="width: 500px"}


### Final Prototype and Application
A front-mounted harvester spray attachment was built to wash spotted lanternflies (SLF) off grape vines immediately before harvest. Water is stored in a refillable tank mounted above the system, then flows through a controllable valve into a PVC pipe network. The pipes have evenly spaced holes arranged in a staggered (checkerboard) pattern to spread water uniformly while minimizing usage. The spray system is supported by a lightweight aluminum frame with rigid 3D-printed joints. Our device is designed to attach to the front of the harvester, extending above the vines below. Water showers onto the vines, penetrating the vines’ verdure and saturating any SLF that may be feasting on the plant. The water serves to encourage them to jump off the plant, or adsorb onto their wings such that they will fall to the ground.

In its current form, our device requires a reliable water source, likely the already established irrigation system on the vineyards or a refillable water tank, and an attachment point to the front of the harvester. The controllable valve means that our device can accommodate the needs of different vineyards or grape plants without wasting resources or causing unnecessary damage. Its minimal design lends itself to infrequent and inexpensive maintenance. Our device is also singular in function, meaning that it does not require an extensive infrastructure of similar devices to perform optimally. As far as the client is concerned, this is an attachment for harvesters to immediately increase yield of harvests by removing SLF from the vines directly before harvester takes them.

### Conclusions and Recommendations
Qualitatively, the results are overall inconclusive. Due to time and resource limitations, a positive pressure system was not implemented, which is necessary to properly spray water through nozzles. Using gravity alone primarily redirects water flow rather than producing a true spray pattern. Although the saturation test was successful, it only measured saturation at ground level and therefore does not accurately represent saturation on the plant canopy.

For further work, the system should be upgraded with directional nozzles driven by a positive pressure system to improve spray efficiency and targeting. It would also be beneficial to incorporate high-pressure air blasts directed at SLF to dislodge insects that are not removed through water application alone.

### Testing and Results

1. Objective: Evaluate integrity and efficacy of water-carrying components.

   (a) Success Criteria: Achieve steady flow rate of 17 mL/s with less than 5% water volume lost to leakage.
   (b) Observations: GUARD expended 1000 mL in 58.1 sec (17 mL/s). Minimal dripping leakage observed.
   (c) Conclusions: Water flow is stable. Connections and piping methods are satisfactory. System is expected to maintain consistent flow during harvesting conditions.

2. Objective: Evaluate whether “checkerboard” hole and pipe distribution enables full area saturation.

   (a) Success Criteria: Achieve saturation of 95% area within cage.
   (b) Observations: Cloth was fully saturated within seconds of operation.
   (c) Conclusions: 100% area coverage was achieved. Future improvements may include directional nozzles or optimized spray methods to improve efficiency and reduce potential plant impact from direct dripping flow.

3. Objective: Evaluate structural integrity of cage.

   (a) Success Criteria: Less than 2 mm of deflection with only one-end support.
   (b) Observations: The frame deflected 0.6 mm under load.
   (c) Conclusions: Structural performance is within acceptable limits. The frame is stable and suitable for scaling while maintaining lightweight rigidity.

### Rough Calculations for Scale

For a typical harvester with an opening width of less than 1 m [3], a similarly scaled layout with comparable depth is estimated to increase the flow rate by a factor of 3.3 relative to the current system, yielding an approximate flow rate of 56.1 mL/s. With a 60-gallon tank, this corresponds to a runtime of approximately 10 hours.

If flow rate efficiency is improved by a factor of 9, the system runtime increases to approximately 10 hours. This level of improvement is considered feasible through the use of improved nozzle technology, replacing the current gravity-driven “waterfall” approach. Overall, the results suggest that with optimized fluid delivery, the system could support continuous operation during harvesting when implemented at full scale.


### Prototype and Testing Details

Our model has two main components: the frame and the pipe structure, designed for a straightforward and lightweight system.

The frame is constructed from 1/2” diameter steel rods, cut into eight 12” pieces and four 11” pieces. 3D-printed corner joints are used to assemble the rods into a cubic structure, with the 11” rods oriented vertically. The top of the cube uses four 12” bars. Two additional 12” bars are mounted 2” below the top on opposite sides using secondary joints, and two more are placed at the bottom on the sides not occupied by the offset bars.

The pipe system uses 3/4” PVC for the main structure. Two 4” sections of 1” schedule 40 PVC are used as hose fittings. Four 13” PVC sections and five 1.75” PVC sections are cut for the network. Each 13” pipe contains two rows of holes separated by 1/2”. One row has holes drilled at odd-inch intervals (1”, 3”, 5”, 7”, 9”, 11”), and the other row has holes at even-inch intervals (2”, 4”, 6”, 8”, 10”).

Four T-connectors are joined in series using the 1.75” PVC segments, including both ends. End caps are placed on one end of the T-connector series and on all 13” pipe sections. The 13” pipes are attached to the T-connectors with holes oriented downward.

A 4” threaded section of 1” schedule 40 PVC is used to connect a threaded barbed hose fitting to the 3/4” PVC at the end of the T-connector series. A 3” length of clear PVC soft tubing (1/2” inner diameter, 5/8” outer diameter) connects the pipe system to the gallon jug reservoir. The jug is connected to a valve via a machined metal nut. The valve is then connected to another 4” threaded section of 1” schedule 40 PVC and a second barbed hose fitting, completing the fluid path.

The pipe assembly is secured to the top of the frame using 3D-printed clips. Two clear PETG sheets are attached to the sides parallel to the pipe direction using zip ties for splash containment and structural guidance.

#### Test Methodology Details

Flow Rate Test: A 1000 mL jug was filled with water. The valve was opened to a fixed position to maintain steady flow, and the time required for full drainage was recorded. The system was also visually inspected for unintended leakage.

Surface Area Test: An absorbent cloth was placed beneath the system. The time required for complete saturation of the cloth was measured, and coverage was visually assessed.

Deflection Test: The structure was secured at one end, and a 6 kg load was applied to the opposite end. A meter stick fixed to the original height was used as a reference to measure deflection accurately.

### Table 1: Final Prototype Component List

| Component | Quantity | Additional Details | Cost |
|----------|----------|--------------------|------|
| Aluminum Rods | 140” | Eight 12” pieces, four 11” pieces | $26.06 |
| Plastic Jug | 1 | N/A | $5.15 |
| PVC Tubing for Air and Water | 3’ | N/A | $2.07 |
| Standard-Wall Unthreaded Rigid PVC Pipe for Water | 60 | 3/4” cut into four 12” pieces, five 7/4” pieces | $5.92 |
| Standard-Wall PVC Pipe Fitting for Water, Tee Connector | 4 | N/A | $3.08 |
| Zinc-Plated Steel Barbed Hose Fitting, for Air and Water | 2 | N/A | $7.72 |
| Standard-Wall PVC Pipe Fitting for Water, Cap | 5 | N/A | $3.00 |
| Plastic Threaded On/Off Valve | 1 | N/A | $5.73 |
| Clear Easy-to-Form PETG Sheet | 2 | N/A | $6.16 |
| Machined Metal Nut (1-12 tpi) | 1 | N/A | $1.00 |
| 1” Schedule 40 PVC (From Lab Scrap Bin) | 8” | Two 4” pieces | $0.00 |
| Corner Joints | 12 | Designed in Fusion, 3D printed out of MLA | $11.94 |
| PVC Clips | 3 | Designed in Fusion, 3D printed out of MLA | $0.91 |
| **TOTAL** |  |  | **$78.74** |


### Table 2: Bill of Materials

| Component | Quantity | Specs | McMaster Code | Cost |
|----------|----------|-------|----------------|------|
| Aluminum Rods | 4 | 3’ each, 1/2” diameter | 8974K28 | $26.80 |
| White HDPE Plastic Jug | 1 | 1 gallon | 46125T7 | $5.15 |
| 18-8 Stainless Steel Cone-Point Set Screw | 1 | Pack of 25, M4 x 0.7 mm thread, 5 mm long | 91217A110 | $2.53 |
| PVC Tubing for Air and Water | 1 | 1/2” ID, 5/8” OD, 25 ft | 5233K66 | $17.25 |
| Standard-Wall Unthreaded Rigid PVC Pipe for Water | 3 | 3/4 pipe size, 5’ each | 48925K92 | $17.55 |
| Standard-Wall PVC Pipe Fitting for Water, Tee Connector | 10 | 3/4 size, socket-connect female, white | 4880K42 | $7.70 |
| Zinc-Plated Steel Barbed Hose Fitting | 2 | Adapter for 1/2” hose ID, 3/4 NPT male | 5350K43 | $7.72 |
| Standard-Wall PVC Pipe Fitting for Water, Cap | 12 | White, 3/4 pipe size socket-connect female | 4880K52 | $7.20 |
| Plastic Threaded On/Off Valve | 1 | 3/4 NPT male x 3/4 GHT male | 9848K46 | $5.73 |
| Heat-Set Inserts for Plastic | 1 | Brass M4 x 0.7 mm, 6.4 mm installed length | 94459A160 | $11.73 |
| Clear Easy-to-Form PETG Sheet | 2 | 12” x 12” x 0.06” | 85815K11 | $6.16 |
| NATSUKY Square Plant Saucer | 1 | 14” (2 pack) | Amazon Link | $19.99 |

---

### Original Components & Machining Costs

| Component | Quantity | Specs | McMaster Code | Cost |
|----------|----------|-------|----------------|------|
| Machined Metal Nut (1-12 tpi) | 1 | 2” round stock, 200g | N/A | $1.00 |
| Machine Shop Time | 6 | N/A | N/A | $30.00 |
| PVC (Lab Scrap Bin) | 1 | 1” schedule 40 PVC, 8” total | N/A | $0.00 |
| Corner Joints | 12 | Designed in Fusion 360 | N/A | $11.94 |
| PVC Clips | 3 | Designed in Fusion 360 | N/A | $0.91 |

---

### Marketing & Miscellaneous Costs

| Component | Quantity | Specs | McMaster Code | Cost |
|----------|----------|-------|----------------|------|
| Original Red Swedish Fish | 1 | Pack of 24 | 1983N13 | $37.78 |
| Werther’s Candy | 1 | 27 oz bag | 1983N11 | $15.38 |
| Fold-Flat Sign (Caution Wet Floor) | 1 | 25” high, 11” wide | 58345T651 | $23.27 |

---

### Total Cost: $255.79

References

[1] https://cals.cornell.edu/integrated-pest-management/outreach-education/whats-bugging-you/spotted-
lanternfly
[2] https://pmc.ncbi.nlm.nih.gov/articles/PMC11285766
[3] https://www.gregoire.fr/en-us/products/wine/881-gl8-6
