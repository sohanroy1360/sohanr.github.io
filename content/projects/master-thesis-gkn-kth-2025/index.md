---
title: "Inverse design of an inter-compressor duct"
date: 2025-06-06
summary: "This project replaces the traditional, month-long manual iterative process with a two-step inverse design algorithm that reduces inter-compressor duct design time to less than a day."

tags:
  - Turbomachinery
  - inter-compressor duct
  - Optimization
  - CFD
  - Engineering design

# Authors: 'me' links to your profile
authors:
  - me
  - Constantin Seemann
  - Jonathan Bergh
  - Blanka Tonsic

image:
  caption: Semi cross-sectional view of an aircraft engine in the axial-radial plane with an inter-compressor duct (marked in red)
  filename: Inter-compressor-duct-Tonsic-et-al
  focal_point: "Smart"

links:
  - name: Full Report
    url: 'RoySeemannMastersThesis.pdf'
    icon_pack: fas
    icon: 📄
    target: '_blank'
---

Traditionally, aero engine components are designed employing a manual iterative design-test-make_changes process. Such methods require the designer's immense experience and few months to even a year. This project develops and validates a two-step inverse design algorithm for aggressive inter-compressor ducts. The method uses a metaheuristic approach for optimizing the duct wall pressure distribution and a Modified Garabedian-McFadden (MGM) algorithm for geometry creation. The optimizer takes less than a day and the MGM algorithm calculates the 3-D geometry from the pressure curve in less than an hour!

<div style="display: flex; gap: 10px; justify-content: center; align-items: center;">
  <div style="flex: 1;">
    {{< youtube kKiNriYDhu4 >}}
  </div>
  <div style="flex: 1;">
    {{< youtube 1hQ_zea5D78 >}}
  </div>
</div>
<p align="center"><em>Evolution of geometry from a straight duct to an ICD (Left: Initial, Right: Optimized)</em></p>
