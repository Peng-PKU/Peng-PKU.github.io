---
# Leave the homepage title empty to use the site title
title:
date: 2025-05-14
type: landing

sections:
  - block: markdown
    content:
      title: Welcome to Topological Magnetism & L-TEM Lab
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
        <span style="font-size: 0.8em; font-weight: bold; margin-top: 0.1em; margin-bottom: 0.1em;">Research</span>
      image:
        filename: welcome.jpg
      text: |
        
        <span style="font-size: 0.8em;">**We investigate topological magnetism and novel spin textures**, focusing on the creation, manipulation, and dynamics of skyrmion and antiskyrmion structures under external stimuli. Our research integrates in situ L-TEM, 3D electron tomography, 4D-STEM, and micromagnetic simulations to reconstruct spin textures and uncover their underlying mechanisms. Our goal is to advance the fundamental understanding of emergent topological states and their field-driven phase transitions toward future spintronic applications.</span>

  - block: markdown
    content:
      title: Current Research Topics
      subtitle: ''
      text: |
        We are offering projects on the following topics to interested students and post-doctoral researchers:
    
        <ol>
          <li>Topological spin textures</li>
          <li>In situ L-TEM control of topological magnetism</li>
          <li>Reconfigurable spintronic functionalities</li>
          <li>3D magnetism tomography and 4D-STEM</li>
          <li>Multiscale magnetic modeling</li>
          <li>Topological magnetic materials, 2D magnetic materials</li>
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
