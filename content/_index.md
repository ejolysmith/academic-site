---
# Leave the homepage title empty to use the site title
title:
date: 2023-09-05
type: landing

sections:
  - block: about.biography
    id: about
    content:
      # title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    id: publications
    content:
      title: Publications
      text: |-
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: markdown
    content:
      title: My title
      text:  APS March Meeting, Exploiting stochastic fluctuations in gene expression to infer interactions between genes. 
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
    id: talks
  - block: collection
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project

---
