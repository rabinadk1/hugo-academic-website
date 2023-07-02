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
    id: experience
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
        - title: Research Assistant 
          company: NepAl Applied Mathematics and Informatics Institute for research (NAAMII)
          company_url: 'https://www.naamii.org.np/'
          company_logo: org-naamii
          location: Lalitpur, Nepal
          date_start: '2021-04-19'
          date_end: ''
          description: |2-
              _Supervisor: Bishesh Khanal, Ph.D._

              - Contributing actively to research projects focused on **Natural Language Processing (NLP)**, **Medical Imaging**, **Semi-supervised Learning**, and **Multi-modal Learning**.
              - Employed rigorous research methodologies to analyze data, draw meaningful conclusions, and contribute to advancing knowledge in these domains.
        - title: Full-stack Developer
          company: Clamphook
          company_url: 'https://clamphook.com/'
          company_logo: org-clamphook
          location: Lalitpur, Nepal
          date_start: '2019-11-01'
          date_end: '2021-06-01'
          description: |2-
              - Participated vigorously in the development of [clamphook.com](https://clamphook.com) by implementing the server-side functionality utilizing _MongoDB_ as the database and _Flask_ as the web framework.
              - Leveraged _React_ as the front-end technology to facilitate seamless communication between the front-end and back-end components of the website.
              - Deployed servers using _nginx_, _gunicorn_, and _Cloudflare_, effectively managing the infrastructure to handle concurrent traffic of up to 5,000 users. This involved ensuring a smooth and uninterrupted user experience even during peak traffic.
        - title: Research Intern
          company: Diyo.ai
          company_url: 'https://diyo.ai/'
          location: Remote
          date_start: '2020-07-01'
          date_end: '2020-12-31'
          description: |2-
              _Supervisor: Binod Bhattarai, Ph.D._
            
              - Conducted extensive research on the availability of Nepali language corpora, resulting in a substantial corpus measuring nearly 3 GB in size.
              - Leveraged the _Huggingface_ transformers library to train an _ALBERT_ language model specifically tailored for the Nepali language.
        - title: Junior Researcher
          company: ASMI
          company_url: 'http://asmi.co/'
          location: Remote
          date_start: '2019-05-01'
          date_end: '2020-03-31'
          description: Researched comprehensively on two-dimensional _In-Video Advertising_, focusing on enabling seamless advertisement integration within platform videos without disrupting the viewing experience. 
    design:
      columns: '2'
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: collection
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: accomplishments
    id: accomplishments
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
        - certificate_url: https://www.coursera.org/account/accomplishments/specialization/certificate/PD5QMDKBSARG
          date_end: ''
          date_start: '2021-04-17'
          description: ''
          organization: DeepLearning.AI
          organization_url: https://www.deeplearning.ai/ 
          title: Generative Adversarial Networks (GANs) Specialization
          url: ''
        - certificate_url: https://www.coursera.org/account/accomplishments/specialization/certificate/6VRS94A69C3V
          date_end: ''
          date_start: '2021-04-19'
          description: ''
          organization: DeepLearning.AI
          organization_url: https://www.deeplearning.ai/ 
          title: Natural Language Processing Specialization
          url: ''
        - certificate_url: https://www.coursera.org/account/accomplishments/specialization/certificate/W7ECP2FEWQFJ
          date_end: ''
          date_start: '2020-06-30'
          description: ''
          organization: DeepLearning.AI
          organization_url: https://www.deeplearning.ai/ 
          title: 'TensorFlow: Data and Deployment Specialization'
          url: ''
        - certificate_url: https://www.coursera.org/account/accomplishments/specialization/certificate/REE4QRCKYDPC
          date_end: ''
          date_start: '2020-06-15'
          description: ''
          organization: University of Michigan
          organization_url: https://www.deeplearning.ai/ 
          title: Applied Data Science with Python Specialization 
          url: ''
        - certificate_url: https://www.coursera.org/account/accomplishments/specialization/certificate/F8S939M8ECVM
          date_end: ''
          date_start: '2020-05-31'
          description: ''
          organization: DeepLearning.AI
          organization_url: https://www.deeplearning.ai/ 
          title: AI for Medicine Specialization
          url: ''
        - certificate_url: https://www.coursera.org/account/accomplishments/specialization/certificate/B5BBPFKDCUES
          date_end: ''
          date_start: '2020-04-18'
          description: ''
          organization: DeepLearning.AI
          organization_url: https://www.deeplearning.ai/ 
          title: Deep Learning Specialization 
          url: ''
        - certificate_url: https://www.coursera.org/account/accomplishments/specialization/certificate/77DPRH7FKG5B
          date_end: ''
          date_start: '2020-04-21'
          description: ''
          organization: DeepLearning.AI
          organization_url: https://www.deeplearning.ai/ 
          title: TensorFlow Developer Specialization 
          url: ''
        - certificate_url: https://www.coursera.org/account/accomplishments/specialization/certificate/B5BBPFKDCUES
          date_end: ''
          date_start: '2020-04-17'
          description: ''
          organization: Imperial College London
          organization_url: https://www.deeplearning.ai/ 
          title: Mathematics for Machine Learning Specialization 
          url: ''
        - certificate_url: https://www.coursera.org/account/accomplishments/specialization/certificate/B5BBPFKDCUES
          date_end: ''
          date_start: '2020-04-18'
          description: ''
          organization: DeepLearning.AI
          organization_url: https://www.deeplearning.ai/ 
          title: Deep Learning Specialization 
          url: ''
        - certificate_url: https://www.coursera.org/account/accomplishments/certificate/7TYPAB5W7SAP
          date_end: ''
          date_start: '2020-04-05'
          description: ''
          organization: Stanford University
          organization_url: https://www.deeplearning.ai/ 
          title: Machine Learning 
          url: ''
    design:
      columns: '2'
  - block: collection
    id: posts
    content:
      title: Recent Posts
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
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Deep Learning
          tag: Deep Learning
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: compact
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'
---
