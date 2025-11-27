---
title: ''
date: 2022-10-24
type: landing

design:
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      username: admin
      text: ''
      button:
        text: Download CV
        url: resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      css_class: hbx-bg-gradient
      avatar:
        size: medium
        shape: circle

  - block: markdown
    content:
      title: '📚 My Research'
      text: |-
        I am a Research Data Analyst at the 
        [Center for Public Health and Human Rights](https://publichealth.jhu.edu/center-for-public-health-and-human-rights)  
        at the [Johns Hopkins Bloomberg School of Public Health](https://publichealth.jhu.edu/).

        My work focuses on:

        • **Structural and social determinants of health**, including studies on  
          [housing and HIV service delivery outcomes](https://pubmed.ncbi.nlm.nih.gov/39817941/),  
          [state-level funding environments](https://www.croiconference.org/wp-content/uploads/sites/2/posters/2024/1225.pdf),  
          [sexual risk stratification](uploads/Abstract_WEPEC157_2024.pdf).

        • **HIV prevention and treatment in China**, including  
          [regimen durability and modification](https://pubmed.ncbi.nlm.nih.gov/41183094/),  
          [delayed treatment initiation](https://pubmed.ncbi.nlm.nih.gov/37416802/),  
          [cost-effectiveness analysis](https://pubmed.ncbi.nlm.nih.gov/35801237/),


        • **Population size estimation** for key populations under  
          [The Global Fund](https://www.theglobalfund.org/),
          [MPact Global Action for Gay Men’s Health and Rights](https://mpactglobal.org/)


        • Creator of the open-source population size estimation and RDS visualization tool:  
          [REDCap RDS Tree Automata & SS-PSE](https://github.com/Yuanqi-Mi/REDCap-RDS-Tree-Automata-SSPSE-/)

      

        I collaborate with partners globally to strengthen infectious diseases response, improve data quality, and advance tools that support equitable resource allocation.  
        Please reach out to collaborate!

    
    design:
      columns: '1'

  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2

  - block: collection
    content:
      title: All Publications
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
---

