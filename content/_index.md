---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: neonowl dot net
      text: a website on the internet since 2001
      primary_action:
        text: YouTube Channel
        url: https://www.youtube.com/neonowl
        icon: brands/youtube
      secondary_action:
        text: Contact Us
        url: /#contact
      announcement:
        text: "Powered by"
        link:
          text: "HugoBlox"
          url: "https://hugoblox.com/?utm_campaign=poweredby"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: bg-neonowl.jpg
          filters:
            brightness: 0.5
---
