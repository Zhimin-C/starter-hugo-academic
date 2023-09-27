---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|1-` multi-line prefix.
      items:
        - title: Research Assistant
          company: Clemson University
          company_url: ''
          location: Greenville.SC
          date_start: '2020-08-01'
          date_end: ''
          description: |1-
              * 3D self-supervised learning
              * 3D semi-supervised learning


    design:
      columns: '2'

  - block: collection
    id: featured
    content:
      title: Recent Publications
      text: |-
      filters:
        folders:
          - publication
        exclude_featured: False
    design:
      columns: '2'
      view: citation
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      # Contact (add or remove contact options as necessary)
      email: zhimnc@clemson.edu
      # phone: 888 888 88 88
      address:
        street: 4 Research Drive
        city: Greenville
        region: SC
        postcode: '29607'
        country: United States
        country_code: US
      # Automatically link email and phone or display as text?
      # Email form provider
    design:
      columns: '2'
---
