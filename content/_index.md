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
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: 'Check out my recent blog posts below!'
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        # The folders to display content from
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        publication_type: ""
        featured_only: false
        exclude_featured: false
        exclude_future: false
        exclude_past: false
      # Choose how many pages you would like to offset by
      # Useful if you wish to show the first item in the Featured widget
      offset: 0
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
    design:
      # Choose a listing view
      view: compact
      # Choose single or dual column layout
      columns: '1'
---
