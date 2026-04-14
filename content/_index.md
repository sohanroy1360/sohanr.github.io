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
      # These flags explicitly tell the block NOT to render those lists
      show_interests: false
      show_education: false
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
      # Page type to display. E.g. post, talk, publication...
      page_type: blog
      # Choose how many pages you would like to display (0 = all pages)
      count: 10
      # Filter on criteria
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: card
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
---
