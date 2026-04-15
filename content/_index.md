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
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Download CV
        url: uploads/CV_sohanr.pdf
      headings:
        about: 'Professional Summary'
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: false
        image:
          filename: F1_wake_CFD.png
          filters:
            brightness: 0.4  # Adjust (0.1 to 1.0) to keep text readable
          size: cover
          position: left
          parallax: true          
      name:
        size: md
      avatar:
        size: medium
        shape: circle

  - block: resume-experience
    content:
      title: Experience
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
    id: papers
    content:
      title: Recent Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation

  - block: resume-skills
    content:
      title: Skills & Hobbies
      username: me
    design:
      columns: '2'

  - block: resume-awards
    content:
      title: Awards
      username: me
    design:
      columns: '2'

  - block: resume-languages
    content:
      title: Languages
      username: me
    design:
      columns: '2'

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
