---
layout: project
title: MAE 2250 Open Design Project
description: Class project on mitigating SLF presence in grape harvests
technologies:
image: /assets/images/prototypemounted.jpg
---

<style>
.project-toc {
  background: #f8f8f8;
  padding: 22px;
  border-radius: 14px;
  margin: 20px 0 35px 0;
  border: 1px solid #e5e5e5;
}

.project-toc h3 {
  margin-top: 0;
}

.project-toc a {
  display: block;
  margin: 10px 0;
  font-weight: 600;
  text-decoration: none;
}

.project-section {
  margin-top: 50px;
  padding-top: 10px;
}

.project-card {
  background: #ffffff;
  padding: 24px;
  border-radius: 14px;
  border: 1px solid #e5e5e5;
  margin: 24px 0;
}

.image-grid {
  display: flex;
  gap: 24px;
  justify-content: center;
  flex-wrap: wrap;
  margin: 26px 0;
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
  border: 1px solid #ddd;
}

.image-card p,
.full-image figcaption {
  margin-top: 8px;
  font-size: 0.92em;
  color: #555;
}

.full-image {
  max-width: 850px;
  margin: 30px auto;
  text-align: center;
}
</style>

## Project Navigation

<div class="project-toc">
  <h3>MAE 2250 Open Design Project</h3>
  <p>This project focuses on mitigating spotted lanternfly contamination during mechanical grape harvesting by preserving usable grape juice and separating liquid from solid material before final collection.</p>

  <a href="#client-pitch">Client Pitch</a>
  <a href="#functional-prototype">Functional Prototype</a>
  <a href="#client-report">Client Report</a>
</div>

<section id="client-pitch" class="project-section" markdown="1">

## Client Pitch

### Spotted Lanternfly Presence During Mechanical Harvesting

**Team:** Tree of Hell  
**Client(s):** Cornell CALS Extension / E&J Gallo Winery / National Grape

<div class="project-card" markdown="1">

**Purpose:**  
The project is designed to address spotted lanternfly contamination during mechanical grape harvesting by separating grape juice from solid material before the final collection stage.

**What Was Proposed:**  
The proposed design separates juice from the grape-bug mixture, then separates bugs from grapes, and finally recombines the grapes and juice during collection.

</div>

### Problem Statement

Currently for growers in upstate New York during the harvest process of vineyards, **Spotted Lanternfly (SLF) presence in grapes during the mechanical harvesting process** is contaminating the product. Trivial solutions are ineffective because harvested grapes are partially liquified during collection and the final product must meet high quality standards.

### Impact

We address the problem at a single point in the harvest process. This modular attachment lowers cost and enables a more efficient harvest by minimizing wasted and dumped product.

### Proposed Direction

During the harvest process, before collection, separate juice from the grape-bug mixture, then separate bugs from grapes. Then combine the grapes and juice again in the collection process.

### Primary Concept

**What it is:**  
A pressurized water tunnel used to separate grapes and SLFs. It can use water pressure or centrifugal force. The design filters juice, then filters SLFs, then remixes the juice and grapes.

**How it would be used:**  
The apparatus would be placed in-line between the harvester and collection systems.

**Why it is better than the status quo:**  
It prevents SLFs from entering the final harvest collection and saves excess or needed grape juice for product production.

**End-of-semester proof of concept:**  
A prototype of the filtration system that shows grapes flowing through while SLFs are successfully separated.

### Client Pitch Sketch

<figure class="full-image">
  <img src="{{ '/assets/images/PosterSketch.jpg' | relative_url }}" alt="Preliminary prototype sketch">
  <figcaption>Preliminary prototype sketch from the client pitch stage.</figcaption>
</figure>

</section>

---

<section id="functional-prototype" class="project-section" markdown="1">

## Functional Prototype

### Functional Prototype Overview

<div class="project-card" markdown="1">

**Purpose:**  
The prototype is designed to separate grape juice from solid material during mechanical harvesting to prevent spotted lanternfly contamination.

**What Was Tested:**  
A perforated tray supported by an adjustable aluminum frame and cable system was tested under load and oscillation conditions to simulate harvesting.

**Outcome:**  
The system showed strong structural performance, minimal deflection, and stable oscillation behavior. It demonstrated effective separation of liquid and solids.

**Next Steps:**  
Future improvements include adding motorized oscillation and improving the adjustability and reliability of the frame system.

</div>

### Functional Prototype Images

<div class="image-grid">
  <div class="image-card">
    <img src="{{ '/assets/images/tray.jpg' | relative_url }}" alt="Final prototype tray">
    <p>Final prototype mounted inside the mock gondola setup.</p>
  </div>

  <div class="image-card">
    <img src="{{ '/assets/images/prototypemounted.jpg' | relative_url }}" alt="Prototype mounted in mock gondola">
    <p>Perforated tray supported by the cable suspension system.</p>
  </div>
</div>

</section>

---

<section id="client-report" class="project-section" markdown="1">

## Client Report

### Proposed Solution and Final Prototype

The final prototype consists of a perforated PVC tray supported by an adjustable aluminum frame, stabilized using a cable suspension system, and enhanced with a motor-driven linkage that generates controlled vibrations. The perforated tray acts as the filtration surface, allowing grape juice to pass through while retaining larger solids, including SLF material.

The system is mounted inside a gondola during harvesting. Grapes and SLF are deposited onto the tray, where the vibrating filtration surface allows juice to pass through while retaining grapes and contaminants. This improves both product quality and total usable yield.

<figure class="full-image">
  <img src="{{ '/assets/images/harvester.png' | relative_url }}" alt="Harvester and field gondola">
  <figcaption>Harvester and field gondola setup.</figcaption>
</figure>

### How It Works

The motor linkage system induces controlled vibrations in the tray during operation. These vibrations help prevent grape skins and other solids from clogging the perforations, allowing liquid to pass through more efficiently. This improves filtration performance and increases the amount of usable juice collected.

### Testing Summary

#### Draining Flow Rate

To evaluate how efficiently liquid could pass through the filtration surface, draining flow rate was tested under two input conditions. In the first test, a water bottle was held directly above the sheet so that the surface stayed flat and the water flowed vertically through the holes. This test measured a flow rate of **3.26 ounces per second per square inch**. In the second test, water was poured several inches above the sheet, allowing the flow to spread across the surface more like it would during harvesting.

<div class="image-grid">
  <div class="image-card">
    <img src="{{ '/assets/images/water.png' | relative_url }}" alt="Water bottle held against perforated tray">
    <p>Flow rate test with water held directly against the filtration surface.</p>
  </div>

  <div class="image-card">
    <img src="{{ '/assets/images/waterheight.png' | relative_url }}" alt="Water poured from above perforated tray">
    <p>Flow rate test with water poured from above the tray.</p>
  </div>
</div>

#### Static Load Capacity

To test whether the prototype could support the weight of harvested material, a static load test was conducted. Weight was added to the straining surface until the prototype reached the maximum tested load of **100 pounds**. During this test, the system remained structurally sound and did not show failure under the applied load.

#### Dynamic Load

To simulate grapes falling onto the straining surface during harvesting, a dynamic load test was performed by dropping bolts from a height of **1 meter** onto the tray. Each bolt weighed **14.3 grams**, and **40 bolts** were dropped during each trial. The prototype withstood the repeated impacts without visible failure.

<figure class="full-image">
  <img src="{{ '/assets/images/bolts.jpg' | relative_url }}" alt="Dynamic load test using bolts">
  <figcaption>Dynamic load test using bolts to simulate falling material during harvest.</figcaption>
</figure>

#### Oscillation Amplitude and Frequency

The vibration system was tested by measuring the motion created by the motor-driven linkage. The prototype produced an oscillation amplitude of **2 cm** and a frequency of **1.11 Hz**. This vibration helps prevent grape skins and other solids from clogging the holes in the tray.

### Conclusion and Recommendation

The final prototype demonstrates a functional and effective approach to reducing contamination and preserving usable grape juice during harvesting. The testing results support the system across multiple success criteria, including fluid-solid separation, structural load support, impact resistance, and controlled vibration.

Based on these results, we recommend continuing development of the design with a focus on improving and refining the vibration system. One key improvement would be integrating a more controlled mechanical actuation system, such as an adjustable motor or linear actuator, to better regulate the amplitude and frequency of oscillation.

Before full implementation, chemical testing should also be conducted to verify that SLF-related contamination has been reduced to acceptable levels. Longer-term field testing in vineyard conditions is also recommended to evaluate durability, performance consistency, and overall effectiveness during extended use.

</section>
