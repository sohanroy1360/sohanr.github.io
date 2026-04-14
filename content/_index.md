---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: about.avatar
    content:
      username: me
      text: |-
        Sohan Roy is a researcher specializing in Fluid Mechanics, with a core focus on computational methods for aerospace, environmental as well as biomedical applications. A graduate of IIT Kharagpur and KTH Royal Institute of Technology, his expertise lies at the intersection of fluid dynamics and numerical methods. Outside of the lab, Sohan is a multi-instrumentalist who finds balance playing the piano and the esraj.
      button:
        text: Download CV
        url: uploads/CV_sohanr.pdf
    design:
      background:
        gradient_mesh:
          enable: true

  - block: resume-experience
    content:
      title: Experience
      username: me
    design:
      columns: '2'

  - block: resume-education
    content:
      title: Education
      username: me
    design:
      columns: '2'

  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        I am a fluid dynamics researcher specializing in computational methods for aerospace and ocean engineering. My work focuses on the application of industrial RANS-based workflows and the development of surrogate modeling techniques to enhance computational efficiency and flow reconstruction. I am actively deepening my expertise in data-driven methods while maintaining a strong research interest in the future application of high-fidelity solvers for complex unsteady aerodynamics.

        Please reach out to collaborate 😃
    design:
      columns: '1'    

  - block: collection
    content:
      title: Recent Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation

  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      page_type: blog
      count: 10
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
      offset: 0
      order: desc
    design:
      view: card
      spacing:
        padding: [0, 0, 0, 0]
---
