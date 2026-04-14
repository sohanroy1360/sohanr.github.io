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
      # THIS HIDES THE FIRST EDUCATION BLOCK
      headings:
        about: 'Professional Summary'
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
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
      filters:
        folders:
          - publications
    design:
      view: citation

  - block: collection
    id: news
    content:
      title: Recent News
      page_type: blog
    design:
      view: card  
---
