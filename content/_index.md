---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
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
      button:
        text: Download CV
        url: uploads/remiroazocar_CV.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: 'Research'
      subtitle: ''
      text: |-
        My research lies on the interface between statistics and health technology assessment, involving both methodological and applied problems. My primary interests are the development of statistical methodology to compare treatments in the absence of head-to-head clinical trials, adjusting for differences in patient populations and overcoming limited access to subject-level data.

        _Current interests: indirect treatment comparisons, covariate adjustment, transportability, estimands_
        
    design:
      columns: '1'
    {{/* 
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
    */}}
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
28.           - event
    design:
      view: article-grid
      columns: 1

    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
