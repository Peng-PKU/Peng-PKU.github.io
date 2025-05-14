---
# Leave the homepage title empty to use the site title
title:
date: 2025-05-14
type: landing

sections:
  - block: markdown
    content:
      title: WELCOME TO PENG GROUP
      subtitle: ''
      text: ''
    design:
      columns: '1'
      background:
        image: 
          filename: title.png
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['40px', '0', '20px', '0']

  - block: hero
    content:
      title: |
        Research
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        <span style="font-size: 0.85em;">**Our group investigates topological magnetism and spintronic device.** Using Lorentz transmission electron microscopy (LTEM), we study real-space spin textures—such as skyrmions, antiskyrmions, and magnetic monopoles—their formation mechanisms, and spin dynamics under electric, thermal, mechanical, and microwave stimuli, complemented by real-time magnetotransport measurements. We further explore their application in spintronic devices.</span>

  - block: markdown
    content:
      title: CURRENT RESEARCH TOPICS
      subtitle: ''
      text: |
        Among other directions, we are offering projects on the following topics to interested students and post-doctoral researchers:
    
        <ol>
          <li>Skyrmion electronics</li>
          <li>Spintronic devices</li>
          <li>Lorentz transmission electron microscopy</li>
          <li>Micromagnetic simulations</li>
          <li>Topological magnetic materials, 2D materials, nanomaterials, heterostructure thin films, superconducting materials</li>
        </ol>
    
        <p>Contact us to learn more!</p>
    design:
      columns: '1'
      background:
        color: "#f0f0f0"
      spacing:
        padding: ['-20px', '0', '-20px', '0']
      css_class: fullscreen

  # - block: collection
  #  content:
  #    title: Latest Prints
  #    text: ""
  #    count: 5
  #    filters:
  #      folders:
  #        - publication
  #      publication_type: 'article-journal'
  #  design:
  #    view: citation
  #    columns: '1'
    
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

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
