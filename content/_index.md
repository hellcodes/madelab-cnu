---
# Leave the homepage title empty to use the site title
title:
date: 2023-11-03
type: landing

sections:
  - block: hero
    content:
      title: |
        <font size="10">Machine Learning and <br> Data Engineering Lab </font>
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        The MADE Lab is a laboratory in Chungnam National University.
        Our mission is to find efficient ML algorithms and achieve self-evolving AI.

        학부 인턴 및 대학원 관심이 있는 학생은 편하게 연락바랍니다.
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
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
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
