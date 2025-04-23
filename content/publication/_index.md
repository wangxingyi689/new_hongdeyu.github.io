---
title: "Publications"
cms_exclude: true

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: collection
    id: papers
    content:
      count: 6
      sort_by: weight
      sort_ascending: true
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        #exclude_featured: True
    design:
      view: citation
  - block: collection
    id: papers
    content:
      count: 6
      sort_by: weight
      sort_ascending: False
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        #exclude_featured: True
    design:
      view: citation

---
