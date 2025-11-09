---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  # Biography section
  - block: resume-biography-3
    content:
      username: admin
      text: ''
      # Show specific sections
      show:
        about: true
        interests: true
        education: true
        work: true
        awards: true
    design:
      css_class: hbx-bg-gradient
      avatar:
        size: medium
        shape: circle

  # Publications section - シンプルなリスト表示
  - block: collection
    id: publications
    content:
      title: Publications
      filters:
        folders:
          - publications
    design:
      view: citation

  # Talks & Presentations section
  # - block: collection
  #   id: talks
  #   content:
  #     title: Talks & Presentations
  #     filters:
  #       folders:
  #         - events
  #   design:
  #     view: compact

  # Experience section
  - block: experience
    id: experience
    content:
      title: Experience
      username: admin
    design:
      columns: '1'

  # Awards section
  - block: awards
    id: awards
    content:
      title: Awards
      username: admin
    design:
      columns: '1'
---
