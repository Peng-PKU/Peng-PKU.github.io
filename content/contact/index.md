---
title: Contact
date: 2025-05-14

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-
        Our group recruits undergraduate students, Ph.D. students, and postdoctoral researchers every year. Interested candidates are welcome to get in touch!
      email: licong.peng@pku.edu.cn
      address:
        street: No.5 Yiheyuan Road, Haidian District
        city: Beijing
        region: CN
        postcode: '100871'
        country: China
        country_code: CN
      coordinates:
        latitude: '39.9996'
        longitude: '116.3054'
      directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      office_hours:
        - 'Weekdays 9:00 to 17:00'
      appointment_url: 'https://calendly.com'
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
      # Automatically link email and phone or display as text?
      autolink: true
    
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: contact.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---
