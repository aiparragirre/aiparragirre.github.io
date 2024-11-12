---
title: 'Software'
date: 2024-05-19
type: landing

design:
  # Section spacing
  spacing: '5rem'

# Page sections
sections:
  - block: collection
    content:
      title: R packages
      text: Here are the latest versions of the R packages I have developed.
      filters:
        folders:
          - software
    design:
      view: article-grid
      fill_image: false
      columns: 2
  - block: collection
    content:
      title: R packages on CRAN
      text: Here are the CRAN versions of the R packages.
    design:
      view: citation
      fill_image: false
      columns: 1
---
