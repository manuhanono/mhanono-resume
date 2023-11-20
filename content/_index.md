---
title: 'Manuel Hanono'
date: 2023-10-24
type: landing

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: about.avatar
    content:
      username: admin
      button:
        label: Download Résumé
        url: uploads/resume.pdf
    design:
      banner:
        # Upload your cover image to the `assets/media/` folder and reference it here
        filename: portada2.jpg
    # kalen-emsley-Bkci_8qcdvQ-unsplash.jpg
  - block: experience
    content:
#      title: Experience
#      username: admin
      items:
         - title: Data & Automation Analyst
        company_name: Siemens Healthineers
        company_url: https://www.siemens-healthineers.com/ar
        company_logo: SH
        date_start: 2023-01-01
        date_end: ''
        summary: |2-
          Responsibilities include:
          - Develop automations for recurring processes
          - Mantain and improve current automations and dashboards
          - Develop new dashboards
          - Migrated dashboards to Qlik Cloud
      - title: Automation Intern
        company_name: Siemens Healthineers
        company_url: https://www.siemens-healthineers.com/ar
        company_logo: SH
        date_start: 2022-08-01
        date_end: 2022-12-31
        summary: |
          Responsibilities include:
          - Migrated infrastructure to a new data center
          - lorem ipsum dolor sit amet, consectetur adipiscing elit
          - lorem ipsum dolor sit amet, consectetur adipiscing elit
    
      - title: Assistant Professor of Applied Statistics
        company_name: Insituto Tecnológico de Buenos Aires
        company_url: ''
        company_logo: ''
        date_start: 2022-08-01
        date_end: ''
        summary: |
          Responsibilities include:
          - Teaching R programming skills
          - Tutoring students during the semester in order for them to develop an applied statistics project

    design:
      # Hugo date format
      date_format: 'January 2006'
      is_education_first: false
  - block: skills
    content:
      title: Skills & Hobbies
      username: admin
  - block: awards
    content:
      title: Awards
      username: admin
  - block: languages
    content:
      title: Languages
      username: admin
---
