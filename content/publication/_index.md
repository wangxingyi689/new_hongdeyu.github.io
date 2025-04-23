---
title: "Publications"
type: landing

design:
  # Default section spacing
  spacing: "0rem"

sections:
  - block: collection
    content:
      count: 6
      sort_by: weight
      sort_ascending: true
      title: ""
      text: ""
      filters:
        folders:
          - publication
        #exclude_featured: True
  - block: collection
    content:
      count: 1
      sort_by: weight
      sort_ascending: False
      title: ""
      text: ""
      filters:
        folders:
          - publication
        #exclude_featured: True
    design:
      css_style: |
        .view-all,
        .btn-view-all,
        a[href="/publication/"] {
          display: none !important;
        }
view: citation
css_style: |
    .view-all,
    .btn-view-all,
    a[href="/publication/"] {
      display: none !important;
    }
---
