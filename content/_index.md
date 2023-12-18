---
# Leave the homepage title empty to use the site title
title:
#date: 2022-10-24
type: landing

sections:
  - block: slider
    content:
      slides:
      - title: test
        content: 
        align: right
        background:
          image:
            filename: model_scales.png
            filters:
              brightness: 0.7
            #class: "custom-image-size" 
          position: center
      - title: Lunch & Learn ☕️
        content: 
        align: left
        background:
          image:
            filename: contact.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
  - block: hero
    content:
      title: 
      image:
        filename: model_scales.png
      #text: |
      #  👋 Welcome
      text: |
          Our research lab focuses on developing theoretical and computational methods to study biological processes across different temporal and spatial scales. We integrate physics, molecular simulations, and machine learning to unravel the mechanisms of essential biological machineries and design molecules for treating related diseases. We strive to build a diverse team, bringing together a wide range of backgrounds and expertise.
 

---


<div style="display: flex; align-items: center;">
    <div>
        {{< figure src="model_scales.png" width="500px" height="auto" caption="" numbered="false" >}}
    </div>
    <div style="margin-left: 20px;">
        <p>👋 Welcome

        Our research lab focuses on developing theoretical and computational methods to study biological processes across different temporal and spatial scales. 
        We integrate physics, molecular simulations, and machine learning to unravel the mechanisms of essential biological machineries and design molecules for treating related diseases. 
        We strive to build a diverse team, bringing together a wide range of backgrounds and expertise.
        </p>
    </div>
</div>

<div style="margin-bottom: 50px;"></div>
