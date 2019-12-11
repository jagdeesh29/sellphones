---
title: Home
sidebar:
  entries:
    - is_primary: true
      title: Home
      url: '#intro'
    - is_primary: false
      title: Who we are
      url: '#one'
    - is_primary: false
      title: Get in touch
      url: '#three'
sections:
  - actions:
      - is_primary: false
        is_scrolly: true
        label: Learn more
        url: '#one'
    background_style: style1
    component: intro.html
    section_id: intro
    subtitle: |-
      Cras aliquam amet adipiscing nibh faucibus suscipit ut Parturient  
      col accumsan est arcu donec sed Eleifend Integer.
    title: Hyperspace
    type: intro
  - background_style: style2
    component: spotlights.html
    section_id: one
    title: Spotlights Section
    type: spotlights
  - background_style: style1
    component: contact.html
    contact_list:
      - text: |-
          12345 Somewhere Road #654
          Nashville, TN 00000-0000
          USA
        title: Address
      - text: user@Hyperspace.tld
        title: Email
        url: '#'
      - text: (000) 000-0000
        title: Phone
    section_id: three
    social:
      social_icons:
        - icon: fa-twitter
          title: Twitter
          url: '#'
        - icon: fa-facebook
          title: Facebook
          url: '#'
        - icon: fa-github
          title: GitHub
          url: '#'
        - icon: fa-instagram
          title: Instagram
          url: '#'
        - icon: fa-linkedin
          title: LinkedIn
          url: '#'
      title: Social
    text: >-
      Phasellus convallis elit id ullamcorper pulvinar. Duis aliquam turpis
      mauris, eu ultricies erat malesuada quis. Aliquam dapibus, lacus eget
      hendrerit bibendum, urna est aliquam sem, sit amet imperdiet est velit
      quis lorem.
    title: Get in touch
    type: contact
menus:
  main:
    title: Home
    weight: 1
layout: home
---

