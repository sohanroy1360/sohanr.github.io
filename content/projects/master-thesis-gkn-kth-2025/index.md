---
title: "Inverse design of an inter-compressor duct"
date: 2025-06-06
summary: "Traditionally, aero engine components are designed employing a manual iterative design-test-make changes process. Such methods require the designer's immense experience and few months to even a year. This project develops and validates a two-step inverse design algorithm for aggressive inter-compressor ducts, reducing design time to less than a day."

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
  caption: "Semi cross-sectional view of an aircraft engine in the axial-radial plane with an inter-compressor duct (marked in red)"
  filename: Inter-compressor-duct-Tonsic-et-al.png
  focal_point: "Smart"

links:
  - name: Full Report
    url: 'RoySeemannMastersThesis.pdf.pdf'
    icon_pack: fas
    icon: 📄
    target: '_blank'
---

 The method uses a metaheuristic approach for optimizing the pressure distribution and a Modified Garabedian-McFadden (MGM) algorithm for geometry creation. The optimizer takes less than a day and the MGM algorithm calculates the geometry from the pressure curve in less than an hour!

 {{< video src="geometry-progression-video.mp4" controls="yes" >}}
 <p align="center"><em> Evolution of geometry from a straight duct to an ICD</em></p>