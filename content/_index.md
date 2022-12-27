---
date: "2022-10-24"
sections:
- block: about.avatar
  content:
    text: null
    username: admin
  id: about
# - block: features
#   content:
#     items:
#     - description: 90%
#       icon: r-project
#       icon_pack: fab
#       name: R
#     - description: 100%
#       icon: chart-line
#       icon_pack: fas
#       name: Statistics
#     - description: 10%
#       icon: camera-retro
#       icon_pack: fas
#       name: Photography
#     title: Skills

- block: portfolio
  content:
    buttons:
    - name: All
      tag: '*'
    - name: PhD
      tag: PhD
    - name: Other
      tag: Other
    default_button_index: 0
    filters:
      folders:
      - project
    title: Projects
  design:
    columns: "1"
    flip_alt_rows: false
    view: showcase
  id: projects



- block: experience
  content:
    date_format: Jan 2006
    items:
    - company: Imperial College London
      company_logo: org-gc
      company_url: ""
      date_end: ""
      date_start: "2021-11-01"
      description: |2-
          Mathematical Modelling of Infectious Diseases:

          * Bayesian Modelling
          * Genetic & Epidemiological analyses
          * Programming (R, C++)
      location: London, UK
      title: PhD Clinical Medical Research
    - company: UCL Institute of Health Informatics
      company_logo: org-x
      company_url: ""
      date_end: ""
      date_start: "2022-05-01"
      description: Research work for the COVID-19 Virus Watch Study “priority analyses” in collaboration with Imperial College.
      location: London, UK
      title: Associate Researcher
    - company: UCL Institute of Epidemiology and Health Care
      company_logo: org-x
      company_url: ""
      date_end: "2022-04-01"
      date_start: "2020-10-01"
      description: |2-
        Virus Watch Study (http://ucl-virus-watch.net/)
        * Analytical tasks 
        * Operational tasks 
        * Teaching Assistant
      location: London, UK
      title: Research Assistant - Data Scientist

    - company: Ministry of the French Armed Forces
      company_logo: org-x
      company_url: ""
      date_end: "2022-08-01"
      date_start: "2020-06-01"
      description: |2-
        * Data extraction, wrangling & analysis
        * Natural Language Processing
        * Classification Modelling
        * Network graphs
        * Mapping

      location: Paris, France
      title: Data Analyst Africa
    title: Experience
  design:
    columns: "2"
    
    
# - block: accomplishments
#   content:
#     date_format: Jan 2006
#     items:
#     - certificate_url: https://www.coursera.org
#       date_end: ""
#       date_start: "2021-01-25"
#       description: ""
#       organization: Coursera
#       organization_url: https://www.coursera.org
#       title: Neural Networks and Deep Learning
#       url: ""
#     - certificate_url: https://www.edx.org
#       date_end: ""
#       date_start: "2021-01-01"
#       description: Formulated informed blockchain models, hypotheses, and use cases.
#       organization: edX
#       organization_url: https://www.edx.org
#       title: Blockchain Fundamentals
#       url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
#     - certificate_url: https://www.datacamp.com
#       date_end: "2020-12-21"
#       date_start: "2020-07-01"
#       description: ""
#       organization: DataCamp
#       organization_url: https://www.datacamp.com
#       title: Object-Oriented Programming in R
#       url: ""
#     subtitle: null
#     title: Accomplish&shy;ments
#   design:
#     columns: "2"

# - block: collection
#   content:
#     count: 5
#     filters:
#       author: ""
#       category: ""
#       exclude_featured: false
#       exclude_future: false
#       exclude_past: false
#       folders:
#       - post
#       publication_type: ""
#       tag: ""
#     offset: 0
#     order: desc
#     subtitle: ""
#     text: ""
#     title: Recent Posts
#   design:
#     columns: "2"
#     view: compact
#   id: posts
# - block: markdown
#   content:
#     subtitle: ""
#     text: '{{< gallery album="demo" >}}'
#     title: Gallery
#   design:
#     columns: "1"
# - block: collection
#   content:
#     filters:
#       featured_only: true
#       folders:
#       - publication
#     title: Featured Publications
#   design:
#     columns: "2"
#     view: card
#   id: featured
# - block: collection
#   content:
#     filters:
#       exclude_featured: true
#       folders:
#       - publication
#     text: |-
#       {{% callout note %}}
#       Quickly discover relevant content by [filtering publications](./publication/).
#       {{% /callout %}}
#     title: Recent Publications
#   design:
#     columns: "2"
#     view: citation
# - block: collection
#   content:
#     filters:
#       folders:
#       - event
#     title: Recent & Upcoming Talks
#   design:
#     columns: "2"
#     view: compact
#   id: talks
# - block: tag_cloud
#   content:
#     title: Popular Topics
#   design:
#     columns: "2"
- block: contact
  content:
    address:
      city: London
      country: United Kingdom
      country_code: UK
      postcode: "W2 1PG"
      street: Medical School Building, St Mary's Hospital, Norfolk Place
    email: c.geismar21@imperial.ac.uk 
    title: Contact
  design:
    columns: "2"
  id: contact
title: null
type: landing
---
