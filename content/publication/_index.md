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
      title: "Publications (example for figure1)"
      text: ""
      filters:
        folders:
          - publication
        #exclude_featured: True
    design:
      columns: '2'
      view: card
  - block: collection
    content:
      count: 1000
      sort_by: weight
      sort_ascending: true
      title: "Publications (example for figure2)"
      text: ""
      filters:
        folders:
          - publication
        #exclude_featured: True
    design:
      columns: '2'
      view: article-grid

  - block: collection
    content:
      count: 1000
      sort_by: weight
      sort_ascending: true
      title: "Publications (example for figure2)"
      text: ""
      filters:
        folders:
          - publication
        #exclude_featured: True
    design:
      view: article-grid

---
