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
      title: Publications1
      text: ""
      filters:
        folders:
          - publication
        #exclude_featured: True
    design:
      columns: 2
      view: card
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
      view: article-grid
      columns: 1
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
      view: article-grid
      columns: 2
  - block: portfolio
    id: projects
    content:
      title: Publications3
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: tag1
          tag: tag1
        - name: tag2
          tag: tag2
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
---
