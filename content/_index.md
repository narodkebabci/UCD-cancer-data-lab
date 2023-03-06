---
# Leave the homepage title empty to use the site title
title: 
date: 
type: landing

sections:
  - block: hero
    content:
      title: 
      image:
        filename: icon_dark.png
      cta:
        label: Research Overview
        url: '/research'
        icon: terminal
        icon_pack: fas
      text: |
        <br>
        The UCD Cancer Data Lab, led by [Dr. Colm J. Ryan]({{< relref "/authors/colm" >}}), use large-scale data analysis to understand how genetic variation in cancer alters molecular interaction networks and to identify ways to target these alterations therapeutically.
        <br>
    design:
      columns: '1'
      css_class: align-items-center
  - block: collection
    content:
      title: Recent News
      subtitle: 
      text: 
      count: 4
      filters:
        folders:
          - news
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
      page_type: post
    design:
      # Choose a layout view
      view: masonry
      columns: '2'
      #spacing: {padding: ["25px", "0", "25px", "0"]}
  - block: markdown
    content:
      title: ''
      subtitle: ''
      text:
        Our group are affiliated with the [UCD School of Computer Science](https://www.ucd.ie/cs/) and based in the [Conway Institute of Biomolecular and Biomedical Research](https://www.ucd.ie/conway/). Various lab members are also affiliated with [Systems Biology Ireland](https://www.ucd.ie/sbi/) and the [SFI Centre for Research Training in Genomics Data Science](https://genomicsdatascience.ie).
    design:
      columns: '1'
      spacing:
      # Customize the section spacing. Order is top, right, bottom, left.
        padding: ["50px", "0", "50px", "0"]
      css_class: align-items-center
---