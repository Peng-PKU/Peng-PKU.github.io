---
# Leave the homepage title empty to use the site title
title:
date: 2025-05-14
type: landing

sections:
  - block: markdown
    content:
      title: WELCOME TO PENG-PKU Lab
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
        
        <span style="font-size: 0.85em;">**We investigate topological magnetism and novel spin textures, focusing on the creation, control, and dynamics of skyrmions, antiskyrmions, and monopole-like structures under external stimuli. We are particularly interested in the three-dimensional reconstruction and mechanism of spin and lattice configurations, using in situ Lorentz TEM, electron tomography, and 4D-STEM, combined with micromagnetic simulations. Our goal is to advance the understanding of topological phase transitions and enable reconfigurable spintronic device concepts.</span>

  - block: markdown
    content:
      title: Current Research Topics
      subtitle: ''
      text: |
        We are offering projects on the following topics to interested students and post-doctoral researchers:
    
        <ol>
          <li>Topological Spin Textures</li>
          <li>In Situ L-TEM Control of Topological Magnetism</li>
          <li>Reconfigurable Spintronic functionalities</li>
          <li>3D Magnetism Tomography and 4D-STEM</li>
          <li>Multiscale Magnetic Modeling</li>
          <li>Topological Magnetic Materials,2D Magnetic Materials</li>
        </ol>
    
        <p>Contact us to learn more!</p>
    design:
      columns: '1'
      spacing:
        padding: ['20px', '0', '20px', '0']


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
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
