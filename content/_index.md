---
# Leave the homepage title empty to use the site title
title:
#date: 2022-10-24
type: landing

sections:
  - block: slider
    content:
      slides:
      - title: Ma Lab
        content: |
            <div style="text-align: center;">
              <hr style="width: 50px; border-top: 4px solid orange; margin: 10px auto;" />
              <div style="color: white;"> Theory · Computation · Biophysics </div>
            </div>
        align: center
        background:
          image:
            filename: cluster.png
            filters:
              brightness: 0.5
            #class: "custom-image-size" 
          position: right
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '300px'
      is_fullscreen: false
      # Automatically transition through slides?
      loop: no
      # Duration of transition between slides (in ms)
      interval: 5000
  - block: markdown
    content:
      title: 
      #image:
      #  filename: model_scales.png
      #text: |
      #  👋 Welcome
      text: |
          Our research lab focuses on developing theoretical and computational methods to study biological processes across different temporal and spatial scales. We integrate physics, multiscale simulations, and machine learning to unravel the mechanisms of essential biological machineries and design molecules for treating related diseases. We strive to build a diverse team, bringing together a wide range of backgrounds and expertise.
 

---

<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-9M5LBVNQ1R"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-9M5LBVNQ1R');
</script>

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
