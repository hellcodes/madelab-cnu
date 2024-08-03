---
# Leave the homepage title empty to use the site title
title:
# date: 2024-02-23
type: landing

sections:
  - block: hero
    content:
      title: |
        <font size="9" color="white">Machine Learning and<br/>Data Engineering Lab </font>
      image:
        filename: welcome.png
      text: |
        <br>
        <font size="4" color="white">
        Our mission is to improve the efficiency of ML algorithms to next levels, to achieve non-trivial algorithms for data-intensive problems, and to develop a parameter-efficient and robust reasoning methodology. We are passionate about tackling significant challenges in various fields such as computer vision and natural language processing, with a focus on addressing fundamental problems. We are seeking talented students to join us on our journey.
        </font>
        <br>
        <font size="4" color="white"><b>학부 인턴 및 대학원 관심이 있는 학생은 편하게 연락바랍니다.</b></font>
    design:
      background:
        # color: "#424242"
        # text_color_light: true

        image:
          filename: main_image.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
    
  - block: collection
    content:
      title: Research Area
      filters:
        folders:
          - area
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      # Choose your content listing view - here we use the `showcase` view
      view: compact
      # For the Showcase view, do you want to flip alternate rows?
      flip_alt_rows: true


  - block: collection
    content:
      title: News
      filters:
        folders:
          - post
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      # Choose your content listing view - here we use the `showcase` view
      view: compact
      # For the Showcase view, do you want to flip alternate rows?
      flip_alt_rows: true
    

  - block: collection
    content:
      title: Projects
      filters:
        folders:
          - projects
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      # Choose your content listing view - here we use the `showcase` view
      view: compact
      # For the Showcase view, do you want to flip alternate rows?
      flip_alt_rows: true

        
---
