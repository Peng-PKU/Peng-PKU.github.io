---
# Leave the homepage title empty to use the site title
title:
date: 2025-5-14
type: landing

sections:
  - block: hero
    content:
      title: |
        Peng Group
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        Our research group focuses on topological magnetism and fundamental spintronic devices. We employ Lorentz transmission electron microscopy (LTEM) to investigate the real-space spin configurations and formation mechanisms of novel topological spin textures—such as skyrmions, antiskyrmions, and magnetic monopoles—in magnetic materials. We explore the spin-related dynamics of these magnetic textures under the excitation of multiple physical fields, including electric current, heat flux, mechanical stress, and microwaves. By integrating real-time magnetic transport measurements, we aim to uncover the microscopic origins of magnetic phenomena. Furthermore, we design and prototype novel spintronic devices using micro- and nanofabrication techniques.
  

  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
