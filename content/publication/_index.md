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
    design:
      view: citation
    #view: citation
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
    #view: citation
    design:
      view: citation
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
