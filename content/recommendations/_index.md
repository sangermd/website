---
title: Library
type: landing

sections:
  - block: markdown
    content:
      title: From My Library
      text: |
        Books, videos, podcasts, and other resources that I have found interesting, enjoyable, and somewhat relevant to my work recently.
    design:
      background: {}

  - block: collection
    content:
      title: ''
      filters:
        folders: ['recommendations']
        exclude_featured: false
        exclude_future: false   # <- show future-dated items too (optional)
        exclude_past: false
      sort_by: date
      sort_ascending: false
      count: 20
    design:
      view: card
      background: {}
---