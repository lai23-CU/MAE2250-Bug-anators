
# Lanternfly Terminator

**Team:** Bug-anators
**Client(s):** Cornell CALS Extension / E\&J Gallo Winery / National Grape  

---

## Table of Contents
- [Client Pitch](#client-pitch)
- [Functional Prototype](#functional-prototype)
- [Final Exhibit & Client Report](#final-exhibit--client-report)

---

## Client Pitch
<a id="client-pitch"></a>

## Problem statement 

Grape farms supplying wineries and juice processors are increasingly impacted by Spotted Lanternflies (SLFs) during the growing and harvesting season. A Penn State-Cornell study found that more than 60% SLFs were harvested directly into 1.5-ton grape bins (up to 80% in some rows). Under current quality standards, a juice load may be rejected if just 1-2 insect fragments are detected in a 1,000-gram core sample. The grape vines also lose vitality after the SLF attaches to the vines. While current strategies focus on applying pesticides, they are too expensive as a constant preventive measure. Our plan focuses specifically on stopping adult SLFs from reaching and settling on vines by intercepting them at key hotspots and entry points in the vineyard. 
  

## Impact
The NY grape industry is valued at $16.81 billion annually, but the increase in SLF infestations causes a significant decrease in this number. By keeping SLFs off grapevines pre-harvest, we reduce infestations. Once SLFs land on vines, they are difficult to control across an area and can rapidly degrade the quality of the harvest. Focusing on this issue lessens SLFs’ impact on product safety, taste, and the economic value of the harvested grapes. 

## Proposed direction(s)

### Concept A (primary): <SLF Automated Scent Trap>

**What it is:** 
Our concept is a scented (Tree of Heaven, etc.) SLF trap that attracts and eliminates them via an electric grid, adhesive, or mechanical suction trap. The device will be weather-proof and self-sufficient (power supply and SLF removal). The SLF would be collected in a section that the users can empty and switch out.

**How it would be used:**
-Set up a trap at hotspot; apply the mechanism
-Scent lures SLF away from the grapevines

**Why it’s better than the status quo:**
-Less Costly than Pesticides
-Avoids repeated harvester tool change

**End-of-semester proof-of-concept:** 
By the semester’s end, we aim to validate the functionality of our auto scent dispersion and elimination methods by testing flying objects similar to SLFs to get the desired response from the mechanism. 

## Key risks / unknowns

-Potential ecological impact on non-target species: Our device’s mechanisms might attract and harm pollinators and beneficial predators, affecting the vineyards’ ecosystem. To derisk: we can use a scent that minimizes the harm done to pollinators and conduct small-scale field tests.
-Maintenance and Usability: Devices require routine maintenance (clear dead insects, refill chemicals, supply power) across many acres of land, thus needing additional labor to operate. To derisk, a bigger capacity can be used to reduce the required maintenance times.


## Questions for the client
Focus on questions they can answer from lived experience.
1. **Is this design worth pursuing given the complex nature of SLF attraction behavior?**  
   *Decision affected:* Whether to prioritize scent engineering or focus solely on mechanical interception.

2. **Could this design realistically reduce SLF presence on grapevines at harvest scale?**  
   *Decision affected:* Whether to design for localized hotspot control or distributed vineyard deployment.

3. **What scents are most attractive to SLFs while minimizing harm to pollinators?**  
   *Decision affected:* Scent selection and ecological mitigation strategy.

4. **How are live SLF hotspot locations currently identified?**  
   *Decision affected:* Whether trap placement should be fixed, mobile, or sensor-guided.

5. **Can traps be placed directly at Tree of Heaven or vine hotspots to eliminate the need for artificial scent dispersal?**  
   *Decision affected:* Whether to simplify system design and remove the active scent mechanism.



## References

- Penn State–Cornell mechanical harvester SLF study (client background source)
- Inspiration for scented insect trap design:  
- Inspiration for scented insect trap design:  
  [Dynatrap Outdoor Insect Trap](https://www.walmart.com/ip/Dynatrap-1-Acre-Outdoor-Insect-Trap/15703653119)



  ---

## Functional Prototype
<a id="functional-prototype"></a>

### Overview

The goal of this prototype is to develop a retractable protective enclosure that prevents spotted lanternflies (SLFs) from reaching grapevines while still allowing easy access for harvesting.

This prototype focuses on validating the **core mechanical behavior of the system**, specifically whether the structure can:
- Expand and contract smoothly  
- Maintain structural integrity under load  
- Operate reliably over repeated use  

The intent of this iteration is not final performance, but to identify **mechanical weaknesses and failure points** before building the final prototype.

This prototype specifically targets the primary mechanical risks identified in our design, including deformation under load, misalignment during motion, and loosening under repeated cycling.

---

## Design Documentation

### Key Mechanisms

**Scissor Linkage System**  
The scissor linkage enables horizontal expansion and contraction of the enclosure. It is the primary mechanism responsible for controlling the system’s motion and maintaining the geometry of the structure during operation.

**Wheel–Rail System**  
The wheel–rail system guides the movement of the structure along a fixed path. It ensures that expansion and contraction occur in a controlled and aligned manner, preventing unwanted lateral motion.

**Rigid Frame**  
The aluminum frame provides structural support for the entire system. It maintains alignment between components and resists deformation during operation.

**Mesh Enclosure (Planned)**  
The mesh is intended to act as a physical barrier to prevent SLFs from reaching the vines while still allowing airflow and light. This component was not included in the current prototype due to part delays, but its integration is critical for the final design.

---

### How It Works

- **Input:** The user manually actuates the system by pushing or pulling the frame  
- **Motion:** The scissor linkage expands or contracts, while the wheel system guides motion along the rail  
- **Output:** The structure transitions between an open state (for access) and a closed state (for protection)  

---

## Design Tests

### 1. Scissor Linkage Structural Test

**What we tested:**  
The ability of the scissor linkage to maintain structural integrity under load without excessive deformation.

**How we tested:**  
Weights were incrementally added in 88 g increments to both sides of the linkage to simulate loading conditions. The resulting tilt of the structure was measured.

**Results:**  
- 88 g → ~6° tilt  
- 176 g → ~10° tilt  
- 264 g → ~10° tilt with audible creaking  
- 352 g → ~10° tilt, stabilized due to screw coupling  

**Takeaway:**  
The linkage remained functional under load, but deformation occurred at relatively low weights. The plateau in tilt suggests the system stabilizes due to joint constraints rather than material stiffness. The creaking indicates that the current wooden material is approaching its structural limits.

**Next iteration:**  
Replace wooden members with aluminum to increase stiffness and reduce deformation. Improve joint design to better resist out-of-plane motion.

---

### 2. Wheel–Rail Motion Test

**What we tested:**  
The ability of the system to move smoothly along the rail without jamming or misalignment.

**How we tested:**  
The system was repeatedly moved back and forth along the full rail length. Instances of jamming and interruptions in motion were recorded.

**Results:**  
- Early cycles: smooth motion with no jamming  
- Later cycles: up to 3 jams per cycle  

**Takeaway:**  
The system generally performs well, but becomes more sensitive to alignment over time. Much of the jamming appears to be caused by inconsistent manual input rather than fundamental design failure.

**Next iteration:**  
Introduce alignment guides or constraints to reduce sensitivity to user input. Implement motorized actuation for more consistent motion.

---

### 3. Fastener Reliability Test

**What we tested:**  
Whether fasteners remain secure under repeated expansion and contraction cycles.

**How we tested:**  
The system was operated for multiple cycles, after which all fasteners were inspected for loosening.

**Results:**  
- Early cycles: 0 loosened fasteners  
- Later cycles: up to 4 loosened fasteners  

**Takeaway:**  
Fasteners progressively loosen due to vibration and repeated motion, reducing system reliability over time.

**Next iteration:**  
Incorporate locking mechanisms such as lock nuts, washers, or thread-locking adhesive. Improve joint design to reduce vibration at connection points.

---

## Success Criteria

**Structural Stability**  
- The structure must remain upright with ≤ 5 in deflection  
- No structural failure after 20 cycles  

**Smooth Motion**  
- The system must travel the full rail length without derailment  
- No interruptions in motion longer than 5 seconds  

**Fastener Reliability**  
- ≤ 10% of fasteners require retightening after 20 cycles  
- No complete fastener failure  

---

## Exhibit Demonstration

The prototype will be demonstrated through repeated expansion and contraction cycles along the rail.

The audience will observe:
- Smooth and continuous motion of the scissor linkage  
- Coordinated interaction between the linkage and wheel–rail system  
- Transition between fully open and fully enclosed configurations  

To provide a quantitative measure of performance, the time required to complete one full cycle will be recorded and compared across multiple trials.

---

## ## Functional Prototype Report
[View Full Functional Prototype Report](https://drive.google.com/file/d/1Aa2GAreDVGRJZIGoRSM6plzzSvkc97bm/view?usp=sharing)


---

## Final Exhibit & Client Report
<a id="final-exhibit--client-report"></a>

### Final Design

Over the course of the semester, our team refined our original spotted lanternfly mitigation concept into a retractable vineyard enclosure designed to prevent SLFs from reaching grapevines while remaining compatible with mechanical harvesting operations.

The final prototype featured:

- Expandable scissor-linkage mechanism
- Wheel–rail guidance system
- Retractable protective enclosure
- Structural support frame
- Mesh barrier for insect exclusion

### Engineering Validation

To evaluate the feasibility of the design, we conducted three primary tests:

#### Structural Stability
Weights were applied to the scissor linkage to evaluate deformation under load. The structure remained functional but experienced measurable tilt, indicating a need for increased rigidity in future iterations.

#### Wheel–Rail Motion Reliability
Repeated expansion and contraction cycles were performed to assess motion consistency. While the system initially operated smoothly, later cycles revealed occasional jamming caused by alignment issues.

#### Fastener Reliability
Fasteners were inspected after repeated operating cycles. Loosening occurred over time due to vibration and repeated motion, highlighting the need for locking mechanisms in future designs.

### Key Findings

The prototype successfully demonstrated the feasibility of a preventative, non-pesticide approach to reducing spotted lanternfly contamination in vineyards.

Future improvements include:

- Aluminum 6061 structural members
- Improved wheel–rail alignment tolerances
- Locking fasteners and vibration-resistant joints
- Motorized actuation
- Full-scale vineyard field testing

### Final Deliverables

- Client Pitch
- Functional Prototype
- Engineering Testing & Validation
- Bill of Materials
- Final Exhibit & Client Report

**Final Exhibit & Client Report**

[View Full Report](https://drive.google.com/file/d/1Aa2GAreDVGRJZIGoRSM6plzzSvkc97bm/view?usp=sharing)
