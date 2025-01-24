---
# Leave the homepage title empty to use the site title
title: ""
date: 2025-01-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      # button:
      #   text: Download CV
      #   url: uploads/resume.pdf
    design:
      css_class: light
      background:
        color: white
        image:
          # Add your image background to `assets/media/`.
          filename: bg1.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: collection
    id: papers
    content:
      title: Publications included in the thesis
      count: 0
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
      sort_by: 'weight'
    design:
      view: citation

---
