---
title: "Transonic Turbine Blade Analysis: VKI LS89"
date: 2024-06-15
summary: "Numerical investigation of transonic flow over turbine guide vanes using RANS, evaluating turbulence model performance and inlet intensity effects."

tags:
  - Turbomachinery
  - Transonic Flow
  - Ansys Fluent
  - CFD

# Authors: 'me' links to your profile
authors:
  - Linus Grinde
  - Augustė Jaškūnaitė
  - Chenyu Lei
  - me

image:
  caption: "Schlieren visualization of density gradients and shock waves on the LS89 blade"
  filename: 1556k_MUR48_Schlieren.png
  focal_point: "Smart"

links:
  - name: Full Report
    url: 'Applied_CFD_project. N1.pdf'
    icon_pack: fas
    icon: 📄
    target: '_blank'
---

This project investigates the aerodynamic performance of the **VKI LS89 transonic turbine guide vane** using computational fluid dynamics. 

The primary focus was the evaluation of various turbulence models ($k-\omega$ SST, $k-\epsilon$, and $\gamma-Re_{\theta}$) in predicting the surface pressure distribution and shock-wave locations under high-subsonic and low-supersonic outlet conditions. Results highlighted the superior ability of the transition model in capturing trailing-edge separation, while also exploring the non-physical yet illustrative impacts of extreme inlet turbulence levels on pressure recovery.