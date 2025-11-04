---
title: 'Experience'
date: 2023-10-24
type: landing

design:
  spacing: '5rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: resume-experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first: Education first = true
      is_education_first: true
  - block: resume-awards
    content:
      title: Honors & Awards
      username: admin
    design:
      view: citation-list  

  - block: markdown
    content:
      title: Professional Credentials
      text: |
        - Professional Engineer – Civil (AK), CE 199699 (2022)  
        - Professional Engineer – Civil (CA), C 94186 (2022)  
        - Professional Engineer – Civil (WA), 22021354 (2022)  
        - FAA-certified Remote Pilot, 4445843 (2021)  
        - Geologist-in-Training (WA), 20120256 (2020)  
        - LEED AP BD+C, 0011101313 (2020)
    design:
      columns: 1
  ---