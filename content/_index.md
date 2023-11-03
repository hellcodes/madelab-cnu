---
# Leave the homepage title empty to use the site title
title:
date: 2023-11-03
type: landing

sections:
  - block: hero
    content:
      title: |
        <font size="10"><b><span style="color:blue">MA</span>chine Learning</b> and <b><span style="color:red">D</span>ata <span style="color:red">E</span>ngineering</b> Lab </font>
      image:
        filename: welcome.jpg
      text: |
        <br>
        <font size="8">
        MADE Lab is a laboratory in Computer Science & Engineering dept., Chungnam National University.
        Our mission is to improve the efficiency of ML algorithms to next levels, to achieve non-trivial algorithms for various data-related problems, and to develop a more parameter-efficient and robust reasoning methodology compared to existing approaches.
        </font>
        <font size="4">학부 인턴 및 대학원 관심이 있는 학생은 편하게 연락바랍니다.</font>
  
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
