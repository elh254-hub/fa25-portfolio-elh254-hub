---
layout: project
title: MAE 2250 Open Design Project
description: Class project on mitigating SLF contamination in grape harvests
technologies:
image: /assets/images/prototypemounted.jpg
---

<style>
.project-toc {
  background: #f7f7f7;
  padding: 18px 22px;
  border-radius: 12px;
  margin: 24px 0 34px 0;
}

.project-toc a {
  display: block;
  margin: 8px 0;
  font-weight: 600;
  text-decoration: none;
}

.project-section {
  margin-top: 45px;
}

.image-grid {
  display: flex;
  gap: 22px;
  justify-content: center;
  flex-wrap: wrap;
  margin: 24px 0;
}

.image-card {
  max-width: 390px;
  text-align: center;
}

.image-card img,
.full-image img {
  width: 100%;
  height: auto;
  border-radius: 12px;
}

.image-card p,
.full-image figcaption {
  margin-top: 8px;
  font-size: 0.95em;
  color: #555;
}

.full-image {
  max-width: 850px;
  margin: 28px auto;
  text-align: center;
}
</style>

## MAE 2250 Overall Project

This project focuses on reducing spotted lanternfly contamination during mechanical grape harvesting. When spotted lanternflies are collected with grapes, they can contaminate the harvested product and reduce the amount of usable grape juice. Because grapes and juice are measured and sold by weight, preserving every ounce of usable product is important for both product quality and vineyard revenue. Our team designed a separation system that rests inside a gondola and filters juice away from solid material while helping prevent clogging during harvest.

<figure class="full-image">
  <img src="{{ '/assets/images/harvester.png' | relative_url }}" alt="Mechanical grape harvester and gondola">
  <figcaption>Example of a grape harvester and field gondola setup.</figcaption>
</figure>

## Project Navigation

<div class="project-toc">
  <a href="#client-pitch">Client Pitch</a>
  <a href="#functional-prototype">Functional Prototype</a>
  <a href="#client-report">Client Report</a>
</div>

---

<section id="client-pitch" class="project-section">

## Client Pitch

### Spotted Lanternfly Presence During Mechanical Harvesting

**Team:** Tree of Hell  
**Client(s):** Cornell CALS Extension / E&J Gallo Winery / National Grape

**Purpose:**  
The original goal of the project was to address spotted lanternfly contamination during mechanical grape harvesting by separating grape juice from solid material before final collection.

**What Was Proposed:**  
Our early concept proposed separating juice from the grape and bug mixture, removing larger contaminants, and preserving as much usable grape product as possible during collection.

### Problem Statement

Growers in upstate New York face the risk of spotted lanternflies entering the harvest stream during mechanical grape harvesting. This is especially challenging because harvested grapes are partially liquified during collection, meaning simple removal methods are not enough. The final product must meet quality standards, and contaminated grapes or juice may become unusable.

### Impact

This project addresses the problem at a single point in the harvest process. A modular attachment could help growers reduce wasted product, protect usable juice, and improve harvest efficiency without requiring a full redesign of existing equipment.

</section>

---

<section id="functional-prototype" class="project-section">

## Functional Prototype

### Functional Prototype Overview

**Purpose:**  
The functional prototype was designed to separate grape juice from solid material during mechanical harvesting while supporting realistic loading conditions.

**Prototype Description:**  
The prototype used a perforated tray supported by an adjustable aluminum frame and cable suspension system. The tray acted as the filtration surface, allowing juice to pass through while larger solids remained on top. The frame helped support the load, while the cable system added stability and allowed controlled motion.

<figure class="full-image">
  <img src="{{ '/assets/images/prototypemounted.jpg' | relative_url }}" alt="Prototype mounted in mock gondola">
  <figcaption>Final prototype mounted inside the mock gondola setup.</figcaption>
</figure>

<div class="image-grid">
  <div class="image-card">
    <img src="{{ '/assets/images/tray.jpg' | relative_url }}" alt="Perforated tray and suspension system">
    <p>Perforated tray supported by the cable suspension system.</p>
  </div>

  <div class="image-card">
    <img src="{{ '/assets/images/prototypemounted.jpg' | relative_url }}" alt="Prototype in gondola frame">
    <p>Prototype positioned inside the gondola frame.</p>
  </div>
</div>

**What Was Tested:**  
The prototype was tested for liquid drainage, static load capacity, dynamic loading, and oscillation behavior. These tests were used to determine whether the design could separate liquid from solids, support harvesting loads, and create a useful sieving motion.

**Outcome:**  
The system showed strong structural performance and demonstrated that liquid could pass through the perforated tray while solids were retained. The prototype also showed that vibration could help improve flow by reducing clogging from grape skins and other solid material.

</section>

---

<section id="client-report" class="project-section">

## Client Report

### Proposed Solution and Final Prototype

The final prototype consists of a perforated PVC tray supported by an adjustable aluminum frame, stabilized with a cable suspension system, and improved with a motor-driven linkage that creates controlled vibration. The device is designed to rest inside a harvest gondola. During operation, grapes, juice, and possible contaminants are deposited onto the tray. The perforated tray allows juice to drain through while larger solids, including grape skins and possible SLF material, remain on top.

The aluminum rods and telescoping frame help distribute weight and support the tray under load. The pin-based height adjustment allows the system to adapt to different harvesting setups. The cable suspension system provides additional support and helps absorb loading when grapes are dumped onto the surface. The motor linkage creates vibration, which helps prevent grape skins and other solids from clogging the holes in the tray. This allows more juice to continue flowing through the system during harvesting.

### How It Works / How It Is Used

The system would be placed inside the gondola during harvest. As grapes and liquid enter the gondola, the mixture lands on the vibrating perforated tray. Juice drains through the holes and is preserved for collection, while larger solids stay above the filtration surface. This helps reduce contamination risk while also preserving usable product. Since harvested grapes and juice are measured by weight, improving the amount of usable juice collected creates a direct economic benefit for growers.

### Testing Summary

#### Draining Flow Rate

The draining flow rate test measured how efficiently liquid could pass through the perforated tray. Water was poured through the tray in two ways: once with the bottle held directly against the surface and once from a higher point above the tray to better represent spreading flow during harvest. The test showed that liquid could pass through the tray while larger solids stayed on top. The measured flow rate was **3.26 ounces per second per square inch**, supporting the success criteria for fluid-solid separation.

<div class="image-grid">
  <div class="image-card">
    <img src="{{ '/assets/images/water.png' | relative_url }}" alt="Water bottle held against perforated tray for flow test">
    <p>Flow rate test with water held directly against the filtration surface.</p>
  </div>

  <div class="image-card">
    <img src="{{ '/assets/images/waterheight.png' | relative_url }}" alt="Water poured from above the perforated tray">
    <p>Flow rate test with water poured from above the tray.</p>
  </div>
</div>

#### Static Load Capacity

The static load test evaluated whether the prototype could support the weight of harvested material. Weight was added to the straining surface until the prototype reached the maximum tested load of **100 pounds**. The system remained structurally sound and did not show failure under the applied load. This supports the idea that the tray and frame can handle significant material inside the gondola.

#### Dynamic Load

The dynamic load test simulated grapes falling onto the tray during harvesting. To approximate impact loading, **40 bolts**, each weighing **14.3 grams**, were dropped from a height of **1 meter**. The prototype withstood the repeated impacts without visible failure, showing that the tray and support structure can handle sudden loading during use.

<figure class="full-image">
  <img src="{{ '/assets/images/bolts.jpg' | relative_url }}" alt="Dynamic load test using bolts">
  <figcaption>Dynamic load test using bolts to simulate falling material during harvest.</figcaption>
</figure>

#### Oscillation Amplitude and Frequency

The vibration system was tested by measuring the motion created by the motor-driven linkage. The prototype produced an oscillation amplitude of **2 cm** and a frequency of **1.11 Hz**. This vibration helps create a sieving motion, which reduces clogging and allows juice to continue flowing through the perforated tray more effectively.

### Conclusion and Recommendation

The final prototype demonstrates a functional approach to preserving usable grape juice while reducing contamination during mechanical harvesting. The testing results show that the system can separate liquid from solids, support harvesting loads, withstand impact, and create a vibration motion that helps prevent clogging. These results suggest that the design is mechanically reliable and has potential to improve filtration efficiency during harvest.

The main recommendation is to continue developing the vibration system. A more controlled actuation system, such as an adjustable motor or linear actuator, should be added so the amplitude and frequency can be tuned for different grape mixtures and moisture conditions. This would make the system more reliable and adaptable in real vineyard environments.

Before full implementation, chemical testing should also be conducted on the collected juice to confirm that SLF-related contamination has actually been reduced to acceptable levels. Longer-term field testing is also recommended to evaluate durability, performance consistency, and effectiveness during real harvesting conditions.

</section>
