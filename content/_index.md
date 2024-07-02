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
        text: Go to YouTube
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
  - block: markdown
    id: contact
    content:
      title: Contact Us
      subtitle: Please use this form
      text: <script charset="utf-8" type="text/javascript" src="//js.hsforms.net/forms/embed/v2.js"></script><script>hbspt.forms.create({region:"na1",portalId:"46644285",formId:"da15afaf-6ce4-4d71-b954-b731b5d651d4"});</script>
      design:
        columns: 1
---
