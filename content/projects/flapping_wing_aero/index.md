---
title: "Numerical evaluation of an asymmetric flapping foil"
date: 2023-04-30
summary: "Conventional rotary propulsion loses 30–50% of energy to non-propulsive axial momentum, whereas bio-inspired flapping foils can reduce this loss to just 10%. Implementing asymmetric kinematics further optimizes these systems for airborne vehicles by tailoring stroke-specific Strouhal numbers."

tags:
  - Biomimetic propulsion
  - Vortices
  - Strouhal number
  - CFD

# Authors: 'me' links to your profile
authors:
  - me

image:
  caption: PRESSURE AND VORTICITY CONTOURS FOR St_0.6 – 0.4 CASE AT t* = 0.25
  filename: contour.png
  focal_point: "Smart"

links:
  - name: Full Report
    url: 'BTP1 report.pdf'
    icon_pack: fas
    icon: 📄
    target: '_blank'
---

Rotating component propulsion generates significant tangential momentum (axially rotating fluid structures), which cannot be used to generate thrust. Flapping foil propulsion averts this problem due to their kinematics, which generate thrust by producing reverse Von-Karman vortices in the plane of motion. Asymmetric flapping foil expands their application to airborne-vehicles by employing asymmetric Strouhal number for up- and down-stroke. This project evaluates various combinations of Strouhal numbers, pivot location and other parameters using RANS laminar simulation.

