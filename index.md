
# Lanternfly Terminator

**Team:** Bug-anators
**Client(s):** Cornell CALS Extension / E\&J Gallo Winery / National Grape  

---

## Table of Contents
- [Client Pitch](#client-pitch)
- [Functional Prototype](#functional-prototype)

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
  https://www.walmart.com/ip/Dynatrap-1-Acre-Outdoor-Insect-Trap/15703653119




  ---

## Functional Prototype
<a id="functional-prototype"></a>

## Overview

The goal of this prototype is to develop a retractable protective enclosure that prevents spotted lanternflies (SLFs) from reaching grapevines while still allowing easy access for harvesting.

This iteration focuses on testing the **mechanical system**, specifically:
- Scissor linkage expansion mechanism  
- Wheel–rail motion system  
- Structural stability of the frame  

---

## Design Documentation

### Key Mechanisms

**Scissor Linkage System**  
Enables horizontal expansion and contraction of the structure.

**Wheel–Rail System**  
Allows the structure to move smoothly along a track.

**Rigid Frame**  
Provides structural support and maintains alignment.

**Mesh Enclosure (Planned)**  
Intended to block SLFs, but not included in this prototype due to part delays.

---

### How It Works

- **Input:** Manual actuation  
- **Motion:** Scissor linkage expands/contracts  
- **Output:** Enclosure opens or closes around vines  

---

## Design Tests

### 1. Scissor Linkage Structural Test

**What we tested:**  
Structural integrity under load  

**How we tested:**  
Added weights in 88g increments to both sides  

**Results:**  
- 88g → ~6° tilt  
- 176g → ~10° tilt  
- 264g → ~10° + creaking  
- 352g → stabilized  

**Takeaway:**  
System works, but material is too weak → switch to aluminum  

---

### 2. Wheel–Rail Motion Test

**What we tested:**  
Smooth motion and jamming  

**How we tested:**  
Repeated full cycles along the rail  

**Results:**  
- Early cycles: no jamming  
- Later cycles: up to 3 jams  

**Takeaway:**  
Mostly reliable; jamming likely due to manual inconsistency → add guides or motor  

---

### 3. Fastener Reliability Test

**What we tested:**  
Whether bolts loosen over time  

**How we tested:**  
Ran multiple cycles and checked fasteners  

**Results:**  
- Early: 0 loosened  
- Later: up to 4 loosened  

**Takeaway:**  
Need locking mechanisms (lock nuts, threadlocker)  

---

## Success Criteria

**Structural Stability**  
- ≤ 5 in deflection  
- No failure after 20 cycles  

**Smooth Motion**  
- No derailment  
- No pauses > 5 seconds  

**Fastener Reliability**  
- ≤ 10% loosening after 20 cycles  

---

## Exhibit Demonstration

We will demonstrate the system by performing repeated expansion and contraction cycles along the rail.

The audience will observe:
- Smooth motion of the scissor linkage  
- Coordinated movement of the system  
- Transition between open and enclosed states  

We will also record the time per full cycle to provide a quantitative performance measure.

---

## Full Report
(https://drive.google.com/file/d/1Aa2GAreDVGRJZIGoRSM6plzzSvkc97bm/view?usp=sharing)
