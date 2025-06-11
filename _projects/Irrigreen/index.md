---
layout: post
title: High-Pressure Sprinkler Cap Redesign
description: 
skills: 
main-image: /cad.png
---

# PressureFit: Leakproof Sprinkler Cap

## Overview

This project involved designing a pressure-resistant, leakproof replacement cap for a smart sprinkler head using FDM 3D printing. The cap needed to handle high water pressure, variable outdoor conditions, and material limitations inherent to consumer-grade additive manufacturing.

## Problem

- **Layer Line Weakness Under Pressure**  
  Early prints failed catastrophically along layer lines when exposed to pressurized water, especially where vertical splits formed along stress paths.

- **Water Sealing Challenges**  
  3D-printed surfaces lack the smoothness and tight tolerances of injection molding, creating persistent leakage issues when threaded or pressed into place.

- **Outdoor Durability**  
  Initial prototypes made in PLA warped or cracked under sun exposure and repeated use.

---

## Technical Approach

### 1. Diagnosing Layer Failure

After observing vertical splits during pressure testing (see *Test 1* below), I researched mechanical failure modes in FDM prints. The brittle fracture followed classic anisotropic stress propagation along Z-layer interfaces. I experimented with several solutions:

- **Angled Print Orientations**  
  Rotated the cap on the build plate to redirect stress diagonally across layer lines.
  
- **Support-Driven Redesigns**  
  Introduced internal slants and interlocking geometry to distribute pressure more evenly across multiple print axes.

- **Stress-Relief Geometry**  
  Added ribs and reinforced flanges to reduce flexing at stress concentrations.

### 2. Achieving Water-Tight Sealing

To address leakage:

- **Compartmentalized Pressure Zones**  
  Redesigned internal flow paths to localize water pressure away from seam-critical areas.

- **Chamfers & Compression Zones**  
  Added tapering and flexible crush-fit sections to simulate a gasket-like seal.

- **Thread Engagement Tuning**  
  Optimized thread depth and spacing to reduce the chance of bypass at threaded interfaces.

### 3. Material & Environmental Optimization

- Switched to **PETG**, chosen for its UV resistance, toughness, and reduced brittleness under pressure.
- All designs were validated under real garden hose pressure and multiple thermal cycles.

---

## Development Gallery

### Prototype Archive
{% include image-gallery.html images="images/Development.jpg" height="300" %}
Ten iterations explored seal geometry, thread engagement, material choice, and print orientation. Each change was tested for pressure integrity and outdoor durability.

### Internal Compartmentalization
{% include image-gallery.html images="images/Change1.jpg" height="300" %}
This redesign added pressure-isolated chambers and sealing flanges. It was a key step in eliminating leak paths around the thread root.

### Failure Analysis
{% include image-gallery.html images="images/Test1.jpg" height="300" %}
This test revealed vertical failure along layer lines under pressure. It led to angled printing strategies, interlocking geometry, and reinforced sealing zones.


---

## Key Outcomes

- **Researched Print Mechanics to Solve Real-World Failure**  
  Diagnosed and addressed layer-oriented splitting using FDM-specific design strategies.

- **Engineered a Leakproof Fit Without Gaskets**  
  Tuned part geometry to take advantage of crush-fit and compression sealing without elastomeric materials.

- **Designed for Harsh Outdoor Conditions**  
  Final cap withstood sun, hose pressure, and repeated use without deformation or leakage.

---