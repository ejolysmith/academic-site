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
      title: Publications & Preprints
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
      title: Presentations
      text: <br />[APS March Meeting](https://meetings.aps.org/Meeting/MAR23/Session/N01.10), March 2023 <br /> *Exploiting stochastic fluctuations in gene expression to infer interactions between genes.* <br /> Contributed talk. <br /> <br />[Biophysique Quebec 2nd Annual Symposium](http://www.biophys.umontreal.ca/BiophysiQ/index.html), October 2022 <br /> *Exploiting stochastic fluctuations in gene expression to infer interactions between genes.* <br /> Contributed talk. <br /> <br />[Canadian Association of Physicists congress](https://www.cap.ca/congress-conference/past-congress/cap2022/), June 2022 <br /> *Inferring causality in gene regulation from static snapshots of gene expression variability.* <br /> Contributed Talk. <br /> <br />[Annual Meeting of the Biophysical Society of Canada](https://event.fourwaves.com/jointbsc2022iupab/pages), May 2022 <br /> *Inferring gene regulation dynamics from static snapshots of gene expression reporters.*  <br /> Contributed poster presentation with talk at student symposium. <br /> <br />[Quantitative Approaches in Biology at Northwestern University](https://www.quantitativebiology.northwestern.edu/conference/), March 2022 <br /> *Fluorescence maturation time:* *a nuisance or a feature?* <br /> Contributed lightning talk and poster presentation. <br /> <br />[APS March Meeting](https://ui.adsabs.harvard.edu/abs/2022APS..MARF04012J/abstract), March 2022 <br /> *Inferring gene regulation from static snapshots of gene expression variability.*  <br /> Contributed talk.  <br />  <br />[Winter q-bio](https://w-qbio.org), February 2022  <br /> *Inferring gene regulation from static snapshots of gene expression variability.* <br /> Contributed talk. <br /> <br /> BiophysiQ Molecular and Cellular Biophysics Virtual Mini-Symposium, November 2021 <br /> *Fluorescent maturation time:* *is it a bug or a feature?* <br /> Contributed talk. <br /> <br />[BactoMontreal 2021 meeting](https://vanteeffelenlab.org/home/bactomontreal/bactomontreal-2021/), October 2021 <br /> *Inferring gene regulation dynamics from static snapshots of gene expression variability.* <br /> Poster presentation. <br /> <br />[EMBO workshop on Physics of Living Systems **:** From Molecules to Tissues](https://meetings.embo.org/event/20-physics-of-living-systems), June 2021 <br /> *Inferring gene regulation dynamics from static snapshots of gene expression reporters.* <br /> Contributed talk. <br /> <br />[Annual Meeting of the Biophysical Society of Canada](https://biophysicalsociety.ca/annual-conference/past-conferences/6th-annual-meeting/),May 2021 <br /> *Inferring gene regulation dynamics from static snapshots of gene expression variability.* <br /> Poster presentation. <br /> <br />RIP Graduate Seminar at the University of Toronto Mississauga, October 2021 <br /> *Inferring gene regulation dynamics from static snapshots of gene expression reporters.* <br /> Invited talk. <br /> <br />[Canadian Association of Physicists Virtual Congress](https://www.cap.ca/congress-conference/past-congress/2020-congress/), June 2020 <br /> *Characteristic variability of co-regulated genes.* <br /> Contributed talk. <br /> <br />[Annual Meeting of the Biophysical Society of Canada](https://biophysicalsociety.ca/annual-conference/past-conferences/5th-annual-meeting/), June 2019 <br /> *Characteristic variability of co-regulated genes.* <br /> Poster presentation. 
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
    id: talks
  - block: collection
    id: projects
    design:
      columns: '2'
      view: compact
    content:
      title: Ongoing Projects
      filters:
        folders:
          - project

---
