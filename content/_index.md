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
      title: News
      text: |
          * **May, 2024**: Dr. Ma won the Early Career Research Award from Cardiovascular Research Institute of Vermont (CVRI) ($10,000). His award has also been selected by the Board of Directors as the Martin M. LeWinter (MMLW) Early Career Investigator Award. <br><br>
          * **Feb, 2024**: Dr. Ma gave a Symposium-select Talk “Exploring allosteric regulation in molecular motors through the computational microscope” at the 68th Biophysical Society Meeting.
  - block: markdown
    content:
      title: 
      text: |
          Our research lab focuses on developing theoretical and computational methods to study biological processes across different temporal and spatial scales. We integrate physics, multiscale simulations, and machine learning to unravel the mechanisms of essential biological machineries and design molecules for treating related diseases. We strive to build a diverse team, bringing together a wide range of backgrounds and expertise. </p>

<div style="margin-bottom: 80px;"></div>

---
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
