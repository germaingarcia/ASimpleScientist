---
date: "2022-10-24"
sections:
- block: about
  content:
    text: null
    username: admin
  id: about
#................................................................................................
- block: features
  content:
    items:
    - description: "**Python**, C++, C#, JS, R, git, LaTeX"
      icon: code
      icon_pack: fa
      name: Programming
    - description: "**D3js**, **Deckgl**, Notebook, colab, Power BI, Tableu"
      icon: chart-simple
      icon_pack: fa
      name: Visual Analytics
    - description: "**Spanish**, **English**, **Portuguese**, Quechua"
      icon: language
      icon_pack: fa
      name: Languages
    title: Skills
#................................................................................................
- block: experience
  content:
    date_format: Jan 2006
    items:
    - company: UNSAAC
      company_logo: logo-unsaac
      company_url: "https://www.unsaac.edu.pe/"
      date_end: ""
      date_start: "2021-09-01"
      description: |2-
          Responsibilities include:

          * Research Projects
          * Business Analytics
      location: Cusco - PERU
      title: University Professor

    - company: UCSP
      company_logo: logo-ucsp
      company_url: "https://ucsp.edu.pe/"
      date_end: "2022-06-30"
      date_start: "2021-01-01"
      description: Posdoctoral research and professor for some data science certifications
      description: |2-
          Responsibilities include:

          * Python for Data Science
          * Bussiness Analytics
          * Dropout Data Analysis
      location: Arequipa - PERU
      title: POS-Doctoral Researcher - Professor
    
    - company: EGEMSA
      company_logo: logo-egemsa
      company_url: "https://web.egemsa.com.pe/"
      date_end: "2014-01-30"
      date_start: "2012-09-01"
      description: Profesional internship in Tecnology of Information Group
      location: Cusco - PERU
      title: Profesional Internship

    title: Experience
  design:
    columns: "2"
#................................................................................................
#- block: accomplishments
#  content:
#    date_format: Jan 2006
#    items:
#    - certificate_url: https://www.coursera.org
#      date_end: ""
#      date_start: "2021-01-25"
#      description: ""
#      organization: Coursera
#      organization_url: https://www.coursera.org
#      title: Neural Networks and Deep Learning
#      url: ""
#    - certificate_url: https://www.edx.org
#      date_end: ""
#      date_start: "2021-01-01"
#      description: Formulated informed blockchain models, hypotheses, and use cases.
#      organization: edX
#      organization_url: https://www.edx.org
#      title: Blockchain Fundamentals
#      url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
#    - certificate_url: https://www.datacamp.com
#      date_end: "2020-12-21"
#      date_start: "2020-07-01"
#      description: ""
#      organization: DataCamp
#      organization_url: https://www.datacamp.com
#      title: Object-Oriented Programming in R
#      url: ""
#    subtitle: null
#    title: Accomplish&shy;ments
#  design:
#    columns: "2"
  
  #................................................................................................
#- block: collection
#  content:
#    count: 5
#    filters:
#      author: ""
#      category: ""
#      exclude_featured: false
#      exclude_future: false
#      exclude_past: false
#      folders:
#      - post
#      publication_type: ""
#      tag: ""
#    offset: 0
#    order: desc
#    subtitle: ""
#    text: ""
#    title: Recent Posts
#  design:
#    columns: "2"
#    view: compact
#  id: posts

#................................................................................................
- block: portfolio
  content:
    buttons:
    - name: All
      tag: '*'
    - name: Crime
      tag: Crime
    - name: Education
      tag: Education
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
#................................................................................................
- block: collection
  content:
    filters:
      featured_only: true
      folders:
      - publication
    title: Featured Publications
  design:
    columns: "2"
    view: card
  id: featured

#................................................................................................
- block: collection
  content:
    filters:
      exclude_featured: true
      folders:
      - publication
    text: |-
      <!-- {{% callout note %}}
      Quickly discover relevant content by [filtering publications](./publication/).
      {{% /callout %}} -->
    title: Recent Publications
  design:
    columns: "2"
    view: citation
- block: collection
  content:
    filters:
      folders:
      - event
    title: Recent & Upcoming Talks
  design:
    columns: "2"
    view: compact
  id: talks
- block: tag_cloud
  content:
    title: Popular Topics
  design:
    columns: "2"
#- block: markdown
#  content:
#    subtitle: ""
#    text: '{{< gallery album="demo" >}}'
#    title: Gallery
#  design:
#    columns: "2"
  

# - block: contact
#  content:
#    address:
#      city: Stanford
#      country: United States
#      country_code: US
#      postcode: "94305"
#      region: CA
#      street: 450 Serra Mall
#    appointment_url: https://calendly.com
#    autolink: true
#    contact_links:
#    - icon: twitter
#      icon_pack: fab
#      link: https://twitter.com/Twitter
#      name: DM Me
#    - icon: skype
#      icon_pack: fab
#      link: skype:echo123?call
#      name: Skype Me
#    - icon: video
#      icon_pack: fas
#      link: https://zoom.com
#      name: Zoom Me
#    directions: 
#    email: germain.garcia@ucsp.edu.pe
#    form:
#      formspree:
#        id: null
#      netlify:
#        captcha: false
#      provider: netlify
#    office_hours:
#    - Monday 10:00 to 13:00
#    - Wednesday 09:00 to 10:00
#    phone: 888 888 88 88
#    subtitle: null
#    text: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis
#      ut magna et, vehicula efficitur enim.
#    title: Contact
  design:
    columns: "2"
  id: contact
title: null
type: landing

---
