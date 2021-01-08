---
title: Home
white_header: true
sections:
  - type: hero_section
    section_id: hero_section
    background_image: images/pexels-photo-1400017.jpg
    background_image_opacity: 80
    content: |
      # Create Your Own Library With One Click.
    actions:
      - title: Shop Now
        url: /store
        arrow: true
        style: primary
  - type: featured_products_section
    section_id: best_sellers_section
    title: Best sellers
    icon: true
    light_title: true
    featured_products:
      - src/pages/products/plant1.md
      - src/pages/products/plant3.md
      - src/pages/products/plant5.md
      - src/pages/products/plant7.md
  - type: featured_categories_section
    section_id: featured_categories_section
    featured_categories:
      - src/pages/category/bigplants.md
      - src/pages/category/cactuses.md
  - type: testimonials_section
    section_id: testimonials_section
    testimonials:
      - author:
          name: Tony EVANS
          location: 'Colorado, USA'
        text: >-
          Honestly one of the best places to find books that will help you grow
          your business!
      - author:
          name: Sonia howard
          location: 'VA, USA'
        text: >-
          I recommend OnlyBookFans to anyone that enjoys reading and is looking
          to better themselves... plus amazing deals!
  - type: promotion_section
    section_id: promotion_section
    title: 'Click, Download, Read'
    subtitle: from $9.99
    image: images/pexels-photo-4855378.jpeg
    cta:
      title: Discover
      url: /store
      style: secondary
template: home
---
