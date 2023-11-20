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
    title: Experience
    username: admin
   
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
  - block: portfolio
    id: projects
    content:
      title: Projects
      subtitle: My subtitle
      text: Add any **markdown** formatted content here - text, images, videos, galleries - and even HTML code!
      filters:
          # Folders to display content from
      folders:
        - project
          # Only show content with these tags
          tags: []
          # Exclude content with these tags
          exclude_tags: []
          # Which Hugo page kinds to show (https://gohugo.io/templates/section-templates/#page-kinds)
          kinds:
            - page
        # Field to sort by, such as Date or Title
        sort_by: 'Date'
        sort_ascending: false
        default_button_index: 0
        buttons:
          - name: All
            tag: '*'
          - name: Data Science
            tag: Data
          - name: Cloud Computing
            tag: Cloud
      design:
        columns: '1'
        view: showcase
        flip_alt_rows: false
---
