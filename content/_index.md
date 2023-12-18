---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: collection
    content:
      title: |
        Ma Lab
      image:
        filename: welcome.jpg
      text: |
        <br>
        Our research lab focuses on developing theoretical and computational methods to study biological processes at different temporal and spatial scales. 
        We integrate physics, molecular simulations, and machine learning to unravel the mechanisms of essential biological machineries and design molecules for treating related diseases. 

  
  - block: collection
    content:
      title: News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
#  - block: markdown
#    content:
#      title:
#      subtitle:
#      text: |
#        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
#    design:
#      columns: '1'

---