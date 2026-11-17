---
{"dg-publish":true,"dg-path":"02_Projects/HelioShade.md","permalink":"/02-projects/helio-shade/","title":"HelioShade","tags":["startup","solar","innovation","entrepreneurship","china","cad","engineering"],"dg-note-properties":{"title":"HelioShade","tags":["startup","solar","innovation","entrepreneurship","china","cad","engineering"]}}
---


![HelioShade Logo](/img/user/3%20GARDEN/content/02_Projects/Logo1.png)

# HelioShade (Startup)

**Status:** Ongoing  
**Location:** Startup in Germany & currently competing in a startup competition in China (Summer 2026)

HelioShade is an innovative startup focused on sustainable, energy-generating infrastructure. We are developing an intelligent, solar-tracking umbrella designed to transform public spaces into smart energy hubs. 

### The Problem
![The Problem](/img/user/3%20GARDEN/content/02_Projects/The%20Problem.png)

Modern urban spaces and hospitality sectors often lack accessible, decentralized renewable energy sources. Traditional shading structures are passive and underutilized, missing a massive opportunity to capture solar energy efficiently throughout the day.

### The Solution
![The Solution](/img/user/3%20GARDEN/content/02_Projects/The%20Solution.png)

HelioShade solves this by integrating smart tracking technology with high-efficiency solar panels. By continuously adjusting to the sun's position, our umbrellas maximize energy generation while providing optimal shade. This turns an everyday object into an independent power station for devices and local microgrids.

---

### Engineering & Prototyping
Developing HelioShade requires a holistic approach to mechanical engineering and smart systems. Below are the visual prototypes and the detailed CAD models that bring our concept to life.

**HelioShade Visual Prototype:**
<video controls src="HelioShade%20Visual%20V1.mp4" width="100%"></video>

**Technical CAD Model:**
<video controls src="CAD%20Model%20of%20HelioShade.mp4" width="100%"></video>

#### Next-Generation Prototype (Model V1)
To rigorously test the system's mechanics, sensors, and algorithmic logic before full-scale manufacturing, we developed a highly optimized 50 cm functional prototype. 

![HelioShade Model V1](/img/user/3%20GARDEN/content/02_Projects/HelioShade-ModelV1-Oben&Unten2.png)

This iteration introduces several critical design upgrades necessary for stability and efficiency:
* **Flexible Thin-Film Solar Foil:** We replaced rigid glass solar panels with a flexible thin-film ETFE foil. This reduces the roof weight by over 80%, mitigating the top-heavy tipping risk and allowing the system to use much smaller, cost-effective stepper motors.
* **Kinematic Balance:** The 2-axis (Pan/Tilt) joint is placed precisely at the center of gravity directly beneath the canopy. Because the umbrella sides balance each other out, the motors only have to overcome friction rather than lifting heavy mass.
* **Ultra-Low Center of Gravity:** All heavy electronics—including the Arduino microcontroller, voltage converters, and the 18650 battery packs—are housed entirely in the heavy base (Sockel). This guarantees that the umbrella will not tip over, even at maximum tilts of up to 150°.

### Weather & Storm Protection System
A critical requirement for autonomous outdoor infrastructure is safety during high-wind events. I developed a programmed safeguard that triggers automatic retraction and locks the system when severe weather thresholds are reached.

> [!tip] Interactive Storm Simulation
> Test the logic and user interface of the weather emergency override system below.
> 
> [🌪️ Click here to launch the Storm Protection Showcase](helioshade_sturmsicherung.html)

---

### Business Plan & Strategy
Beyond the technical engineering, developing a scalable business model is critical to our success, especially as we actively pitch to investors and present our startup in China. 

[📄 Click here to view/download the full HelioShade Business Plan (PDF)](HelioShade%20BP.pdf)