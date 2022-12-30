---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
 
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: features
    content:
      title: Skills
      items:
        - name: Finance
          description: 90%
          icon: r-project
          icon_pack: fab
        - name: Computer science
          description: 60%
          icon: chart-line
          icon_pack: fas
        - name: Psychology
          description: 50%
          icon: camera-retro
          icon_pack: fas
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
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Lecturer
          company: Guangzhou Huashang Vocational College
          company_url: ''
          company_logo: org-x
          location: Guangzhou, China
          date_start: '2021-09-01'
          date_end: ''
          description: |2-
              Responsibilities include:

              * Responsible for the teaching of financial statement analysis, big data, fund investment, financial laws and other courses.
              * Preside over scientific research of the faculty team, and engage in other research projects as a core member.
              * Join the textbook compilation group and participate in various ability competitions and professional skill trainings.	
        - title: Management Trainee
          company: GF Securities Guangzhou Zengcheng business department 
          company_url: ''
          company_logo: org-x
          location: Guangzhou, China
          date_start: '2020-05-01'
          date_end: '2020-06-01'
          description: |2-
              Responsibilities include:

              * Participate in the company's morning meeting, master and track the daily dynamics of the capital market.
              * Read and excavate the financial reports of listed companies, and write research reports.
              

        - title: Management Trainee
          company: South China Normal University Management Office 
          company_url: ''
          company_logo: org-x
          location: Guangzhou, China
          date_start: '2019-06-01'
          date_end: '2019-08-01'
          description: |2-
              Responsibilities include:

              * Responsible for a series of copywriting and report production, put forward analysis reports. 
              * Responsible for personnel management, personnel training and public relations events. Regularly conduct compliance checks on employees' attendance and work.
              

        - title: Personal Loan Department and Sales     Department Manager
          company: ICBC
          company_url: ''
          company_logo: org-x
          location: Guangzhou, China
          date_start: '2017-07-01'
          date_end: '2017-09-01'
          description: |2-
              Responsibilities include:

              * Review, scanning, entry and filing of personal loan customer data, and improve the bank loan database.	
              * Familiar with banking business, guide and handle business according to customer needs.
              * Assist the manager to carry out credit investigation and audit, sort out credit files and make data forms.

    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://www.coursera.org
          date_end: ''
          date_start: '2021-01-25'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Neural Networks and Deep Learning
          url: ''
        - certificate_url: https://www.edx.org
          date_end: ''
          date_start: '2021-01-01'
          description: Formulated informed blockchain models, hypotheses, and use cases.
          organization: edX
          organization_url: https://www.edx.org
          title: Blockchain Fundamentals
          url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
        - certificate_url: https://www.datacamp.com
          date_end: '2020-12-21'
          date_start: '2020-07-01'
          description: ''
          organization: DataCamp
          organization_url: https://www.datacamp.com
          title: 'Object-Oriented Programming in R'
          url: ''
    design:
      columns: '2'
  - block: collection
    id: posts
    content:
      title: Recent Publications
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '2'
  
 
  # - block: collection
  #   id: featured
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     columns: '2'
  #     view: card
  

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        To contact the author, please fell free to use any of the following methods.
      # Contact (add or remove contact options as necessary)
      email: danzuo2-c@my.cityu.edu.hk
      phone: +86 13539928698
      # appointment_url: 'https://calendly.com'
      # address:
      #   street: 450 Serra Mall
      #   city: Stanford
      #   region: CA
      #   postcode: '94305'
      #   country: United States
      #   country_code: US
      # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      office_hours:
        - 'Monday-Sunday 08:00 to 22:00'
        
      # contact_links:
      #   - icon: twitter
      #     icon_pack: fab
      #     name: DM Me
      #     link: 'https://twitter.com/Twitter'
      #   - icon: skype
      #     icon_pack: fab
      #     name: Skype Me
      #     #link: 'skype:echo123?call'
      #   - icon: video
      #     icon_pack: fas
      #     name: Zoom Me
      #     link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
