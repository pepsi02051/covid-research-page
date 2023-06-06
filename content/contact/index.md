---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-
        This is an example contact page
      email: examplet@hku.hk
      phone: 000 000 0000
      address:
        street: HKTP
        city: Hong Kong
        region: Sha Tin
        postcode: '999077'
        country: China
        country_code: CN
      coordinates:
        latitude: '22.431172'
        longitude: '114.201696'
      directions: W19
      office_hours:
        - 'Monday 00:00 to 00:00'
        
      appointment_url: 'https://www.hku.hk/'
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
