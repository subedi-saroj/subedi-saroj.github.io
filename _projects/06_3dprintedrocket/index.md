---
layout: post
title: Ecofriendly Air-Powered Seed Rocket for Reforestation
description: Designed and built an air-powered rocket to disperse seeds in hazardous or difficult-to-access areas, using biodegradable materials and additive manufacturing. Combined SLA, SLS, and FDM printing to fabricate different components, and validated performance through open-source rocket flight simulations, achieving ~70 m horizontal travel.
skills:
  - Additive Manufacturing (SLA, SLS, FDM)
  - Rocket Design & Simulation
  - Materials Selection (ABS, Tough 2000, PA12 Nylon)
  - Prototyping & Testing
main-image: /assets/images/projects/main.jpg
---
## Background
Seed dispersal in hazardous or inaccessible environments (e.g., post-wildfire zones, steep slopes) is difficult to achieve using conventional replantation methods. This project aimed to design an **air-powered, biodegradable seed rocket** to deliver seeds over long distances with minimal environmental impact.

## Design
- **Nose Cone (SLA, Tough 2000):** parabolic profile for low drag and weight balancing.
- **Seed Payload (SLS, PA12 Nylon):** complex internal geometry with no supports required.
- **Fins & Launching Base (FDM, ABS):** self-supported geometry, integrated for stability.

{% include image-gallery.html images="rocket.jpg" height="500" %}
{% include image-gallery.html images="fdm.jpg" height="500" %}
{% include image-gallery.html images="sls.jpg" height="500" %}
{% include image-gallery.html images="sla.jpg" height="500" %}

## Delivery Method
- **Spiral screw-style payload release** for passive mid-flight seed ejection.
- Optimized fin shape (clipped delta with rounded leading edge, wedge trailing edge) to maximize stability.

## Cost & Time Summary
| Part             | Process | Material       | Print Time       | Cost   |
|------------------|---------|----------------|------------|--------|
| Fins & Base      | FDM     | ABS            | 9 hr 15 m  | $144.10|
| Nose Cone        | SLA     | Tough 2000     | 3 hr 23 m  | $17.29 |
| Payload Section  | SLS     | PA12 Nylon     | 8 hr 30 m  | $159.26|
| **Total**        | —       | —              | ~21 hr     | $320.65|

## Simulation
- Simulated using open-source rocket flight software.  
- Parameters: wind speed = 2 m/s, AoA = 45°, launch impulse = 10 Ns.  
- **Result:** Achieved ~70 meters horizontal distance.
{% include image-gallery.html images="sim.jpg" height="500" %}
