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
      subtitle: My subtitle
      text: ***APS March Meeting 2023***,
Exploiting stochastic fluctuations in gene expression to infer interactions between genes. (Contributed talk) \
***Biophysique Quebec 2nd Annual Symposium 2022***, 
Exploiting stochastic fluctuations in gene expression to infer interactions between genes. (Contributed talk) \
Canadian Association of Physicists congress, June ’22
Inferring causality in gene regulation from static snapshots of gene expression variability. Contributed talk
Annual Meeting of the Biophysical Society of Canada, May ’22
Inferring gene regulation dynamics from static snapshots of gene expression reporters. Contributed poster presentation with talk at student symposium
4th Annual Conference on Quantitative Approaches in Biology at Northwestern University, March ’22 Fluorescence maturation time: a nuisance or a feature?
Contributed lightning talk and poster presentation
APS March Meeting 2022, March 22’
Inferring gene regulation from static snapshots of gene expression variability. Contributed talk
Winter q-bio meeting, February 22’
Inferring gene regulation from static snapshots of gene expression variability. Contributed talk
BiophysiQ Qu ́ebec Molecular and Cellular Biophysics Virtual Mini-Symposium, November 21’ Fluorescent maturation time: is it a bug or a feature?
Contributed talk
BactoMontreal 2021 meeting, October 21’
Inferring gene regulation dynamics from static snapshots of gene expression variability. Poster presentation
Presented for the Nancy Papalopulu Lab and the Cerys Manning Lab at the University of Manchester, June 21’ Inferring gene regulation dynamics from static snapshots of gene expression reporters.
Invited talk
EMBO workshop on Physics of Living Systems: From Molecules to Tissues, June 21’ Inferring gene regulation dynamics from static snapshots of gene expression reporters. Contributed talk
Annual Meeting of the Biophysical Society of Canada, May 21’
Inferring gene regulation dynamics from static snapshots of gene expression variability. Poster presentation
RIP Graduate Seminar in the CPS department at University of Toronto Mississauga, October 21’ Inferring gene regulation dynamics from static snapshots of gene expression reporters.
Invited talk
Canadian Association of Physicists Virtual Congress, June 20’ Characteristic variability of co-regulated genes.
Contributed talk
Annual Meeting of the Biophysical Society of Canada, June 19’ Characteristic variability of co-regulated genes.
Poster presentation
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
