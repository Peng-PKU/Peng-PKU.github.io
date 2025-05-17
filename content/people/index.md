---
title: People
date: 2025-05-14

type: landing

sections:
  - block: markdown
    content:
      title: Meet the Team
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
    
  - block: people
    content:
      title: 
      text: >
        <span style="font-size: 1.25rem;">
        We are the <em>Topological Magnetism & L-TEM Lab</em>,  
        a research subgroup within the broader team led by  
        <a href="https://faculty.pku.edu.cn/houyanglong/zh_CN/xsxx/50668/list/index.htm" target="_blank">Prof. Yanglong Hou</a> at Peking University.  
        Below are the main members of our lab.
        </span>
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          - Principal Investigators
          - Postdoctoral Researcher
          - Grad Students
          - Administration
          - Visitors
          - Alumni
      sort_by: Params.sort_order
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true
---
