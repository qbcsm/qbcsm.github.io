---
# Leave the homepage title empty to use the site title
title:
date: 2025-05-18
type: landing

sections:
  - block: hero
    content:
      title: |
        Quantum Beams & Computation for Sustainable Materials group
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        Based in the Materials Physics Center in Donostia San Sebastián, we are focused on the use and development of neutron-based and computation techniques to improve our knowledge of energy materials

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: group.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['0', '0', '0', '0']
      css_class: fullscreen

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./tour/" cta_text="Get the tour →" %}}
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'

  - block: collection
    content:
      title: Recent & Upcoming Events
      subtitle:
      text:
      count: 4
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: event
    design:
      view: card
      columns: '1'

  - block: collection
    content:
      title: Latest Publications
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type:
    design:
      view: citation
      columns: '1'

  - block: collection
    content:
      title: Outreach activities
      subtitle:
      text:
      count: 4
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: outreach
    design:
      view: card
      columns: '1'
---
