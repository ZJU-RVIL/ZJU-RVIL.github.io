---
# Leave the homepage title empty to use the site title
title:
date: 2024-09-01
type: landing

sections:
  - block: slider
    content:
      slides:
      - title:  Welcome to the Robotics Vision and Intelligence Lab
        content: 
        align: center
        background:
          image:
            filename: zjui_scene.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'

    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000

  - block: hero
    content:
      title: Introduction 
      text: |
        <br>
        xxxxx

    design:
      background:
      # Choose colors such as from https://html-color-codes.info
          gradient_start: '#003f88'
          gradient_end: '#eeeeee'
          gradient_angle: 45
          # Text color (true=light, false=dark, or remove for the dynamic theme color).
          text_color_light: true
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
      text:  
    design:
      # view: showcase 
      view: compact
      columns: '2'

  - block: collection
    content:
      text: ""
      title: Featured Publications
      count: 5
      filters:
        folders:
          - publication
        publication_type: ''
    design:
      view: compact
      columns: '2'

---
