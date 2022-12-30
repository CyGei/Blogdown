---
date: "2022-10-24"
sections:
- block: about.avatar
  content:
    text: null
    username: admin
  id: about


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
      company_logo: imperial
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
      company_logo: UCL
      company_url: ""
      date_end: ""
      date_start: "2022-05-01"
      description: Research work for the COVID-19 Virus Watch Study “priority analyses” in collaboration with Imperial College.
      location: London, UK
      title: Associate Researcher
    - company: UCL Institute of Epidemiology and Health Care
      company_logo: UCL
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
      company_logo: army
      company_url: ""
      date_end: "2020-08-01"
      date_start: "2020-06-01"
      description: |2-
        * Data extraction, wrangling & analysis
        * Natural Language Processing
        * Classification Modelling
        * Network graphs
        * Mapping

      location: Paris, France
      title: Data Analyst Africa
      

    - company: Distinction
      company_logo: UCL
      company_url: ""
      date_end: "2020-09-01"
      date_start: "2019-09-01"
      description: |2-
        * Quantitative route
        * [Course description](https://www.ucl.ac.uk/prospective-students/graduate/taught-degrees/applied-infectious-disease-epidemiology-msc)
      location: London, UK
      title: MSc. Infectious Disease Epidemiology
           
    - company: 2:1
      company_logo: UCL
      company_url: ""
      date_end: "2019-09-01"
      date_start: "2016-09-01"
      description: |2-
        * **Economics & Data Science route**
        * [Course description](https://www.ucl.ac.uk/prospective-students/graduate/taught-degrees/applied-infectious-disease-epidemiology-msc)
      location: London, UK
      title: BSc. Philosophy, Politics & Economics
           
      
      
    title: Experience
  design:
    columns: "2"
  id: experience
  
  
    
    
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
