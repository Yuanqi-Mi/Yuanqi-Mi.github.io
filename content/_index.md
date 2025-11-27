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
        url: uploads/resume.pdf
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


        • **Structural and social determinants of health**, including work on 
  [homelessness and HIV prevention](https://pubmed.ncbi.nlm.nih.gov/39817941/),
  [state-level funding environment] (https://www.croiconference.org/wp-content/uploads/sites/2/posters/2024/1225.pdf/),
  [sexual risk profiles among clients of FSW in South Africa (AIDS 2024)](uploads/Abstract_WEPEC157_2024.pdf).

  
         • **HIV prevention and treatment in China**, including work on  
  [antiretroviral therapy regimen modification](https://pubmed.ncbi.nlm.nih.gov/41183094/),  
  [treatment initiation](https://pubmed.ncbi.nlm.nih.gov/37416802/),  
  [Cost-effectiveness of pre-exposure prophylaxis](https://pubmed.ncbi.nlm.nih.gov/35801237/).


        • **Population size estimation** of key populations for 
          [The Global Fund](https://www.theglobalfund.org/)

        • **Development of epidemiologic tools**, including  
          **Respondent-driven sampling (RDS)**  
          ([method overview](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2390692/))  
          and weighting systems in  
          [R],  
          [Python], and  
          [STATA]
    
        • Creator of the open-source RDS visualization and SS-PSE tool:  
          👉 **REDCap RDS Tree Automata**  
          https://github.com/Yuanqi-Mi/REDCap-RDS-Tree-Automata-SSPSE-/

        • **Big data** integrating behavioral, clinical, and multi-country datasets

        I collaborate with partners globally to improve HIV surveillance, strengthen data quality, and develop tools that enhance equitable resource allocation.  
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
