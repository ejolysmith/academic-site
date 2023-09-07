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
      title: Talks
      text: APS March Meeeting, March 2023 <br /> Exploiting stochastic fluctuations in gene expression to infer interactions between genes. <br /> Contributed talk. <br /> <br /> Biophysique Quebec 2nd Annual Symposium, October 2022 <br /> Exploiting stochastic fluctuations in gene expression to infer interactions between genes. Contributed talk. <br /> <br /> Canadian Association of Physicists congress, June 2022 <br /> Inferring causality in gene regulation from static snapshots of gene expression variability. <br /> Contributed Talk. <br /> <br /> Annual Meeting of the Biophysical Society of Canada, May 2022 <br /> Inferring gene regulation dynamics from static snapshots of gene expression reporters.  <br /> Contributed poster presentation with talk at student symposium. <br /> <br /> 4th Annual Conference on Quantitative Approaches in Biology at Northwestern University, March 2022  <br /> Fluorescence maturation time: a nuisance or a feature? <br /> Contributed lightning talk and poster presentation.
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
