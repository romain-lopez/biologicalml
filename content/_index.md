---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "3rem"

sections:
  - block: header-landing
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Our Research
        url: projects/
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: Header_Image.jpg
          filters:
            brightness: 0.6
          size: cover
          position: center
          parallax: false
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Our Research
        url: projects/
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: Header_Image.jpg
          filters:
            brightness: 0.6
          size: cover
          position: center
          parallax: false


  - block: markdown
    content:
      title: '📚 Our Research Group'
      subtitle: ''
      text: |-
        The Biological Machine Learning Group, led by <a href="people/" target="_blank">Romain Lopez</a>, aims to advance the field of machine learning, and apply those techniques to enhance our understanding of biological systems. Our interdisciplinary research focuses on understanding the complex interactions and dynamics of cellular populations, particularly in the immune system, to drive discoveries in biology and medicine.

        We are primarily affiliated with the <a href="https://cs.nyu.edu/" target="_blank">Computer Science Department</a> of the <a href="https://cims.nyu.edu/" target="_blank">Courant Institute for Mathematical Sciences</a> and the <a href="https://as.nyu.edu/departments/biology.html" target="_blank">Biology Department</a> of <a href="https://as.nyu.edu/" target="_blank">New York University</a>. We are also affiliated with the <a href="https://cds.nyu.edu/" target="_blank">Center for Data Science</a>.
    # design:
    #   columns: '1'
  # - block: collection
  #   id: papers
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     view: article-grid
  #     columns: 2
  # - block: collection
  #   id: news
  #   content:
  #     title: Recent News
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: post
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: date-title-summary
  #     # Reduce spacing
  #     spacing:
  #       padding: [0, 0, 0, 0]

---
