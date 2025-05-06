---
title: "Publications"
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: collection
    content:
      count: 1000
      sort_by: weight
      sort_ascending: true
      title: "Publications"
      text: ""
      filters:
        folders:
          - publication
        #exclude_featured: True
    design:
      view: citation
  - block: collection
    content:
      count: 1000
      sort_by: weight
      sort_ascending: true
      title: "Publications1"
      text: ""
      filters:
        folders:
          - publication
        #exclude_featured: True
    design:
      columns: 2
      view: cardtest
  - block: collection
    content:
      count: 1000
      sort_by: weight
      sort_ascending: true
      title: "Publications2"
      text: ""
      filters:
        folders:
          - publication
        #exclude_featured: True
    design:
      view: cardtest
      columns: 1
  - block: collection
    content:
      count: 1000
      sort_by: weight
      sort_ascending: true
      title: "Publications3"
      text: ""
      filters:
        folders:
          - publication
        #exclude_featured: True
    design:
      view: article-grid
      columns: 2

---
