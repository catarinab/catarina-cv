---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '1'
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
        - title: Researcher
          company: INESC-ID
          company_url: 'https://www.inesc-id.pt/'
          company_logo: inesc
          location: Lisboa, Portugal
          date_start: '2023-10-04'
          date_end: ''
          description: |2-
              Parallelization of the Krylov Method for the Calculation of the Mittag-Leffler Function
        - title: Teaching Assistant
          company: Instituto Superior Técnico
          company_url: 'https://tecnico.ulisboa.pt/en/'
          company_logo: ist
          location: Lisboa, Portugal
          date_start: '2022-09-19'
          date_end: ''
          description: Teaching Computer Organization at a Bsc Level and Parallel and Distributed Computing at a Msc Level.
    design:
      columns: '2'
  - block: experience
    id: education
    content:
      title: Education
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Master Degree in Computer Science and Engineering
          company: Instituto Superior Técnico
          company_url: 'https://tecnico.ulisboa.pt/en/'
          company_logo: ist
          location: Lisboa, Portugal
          date_start: '2022-09-19'
          date_end: ''
        - title: Bologna Degree in Computer Science and Engineering
          company: Instituto Superior Técnico
          company_url: 'https://tecnico.ulisboa.pt/en/'
          company_logo: ist
          location: Lisboa, Portugal
          date_start: '2019-09-09'
          date_end: '2022-07-08'
        - title: Entrepreneurship Summer Programme
          company: European Innovation Academy
          company_url: 'https://www.inacademy.eu/'
          company_logo: eia
          location: Cascais, Portugal
          date_start: '2019-08-01'
          date_end: '2019-08-20'
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
        - certificate_url: https://www.cambridgeenglish.org/exams-and-tests/proficiency/
          date_end: ''
          date_start: '2022-01-08'
          description: ''
          organization: Cambridge
          organization_url: https://www.cambridgeenglish.org/exams-and-tests/proficiency/
          title: C2 Proficiency
          url: ''
        - certificate_url: https://courses.elearning.tecnico.ulisboa.pt/certificates/cd68373f17024d188cc911a6500eb0fc
          date_end: ''
          date_start: '2023-02-01'
          description: ' Instituto Superior Técnico - MOOC Platform'
          organization: IST
          organization_url: https://courses.elearning.tecnico.ulisboa.pt/
          title: Data Science - Classification
          url: 
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact me
      # Contact (add or remove contact options as necessary)
      email: catarina.c.bento@tecnico.ulisboa.pt
      phone: 00351 911710980
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---
