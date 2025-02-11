---
Title: Research

# Listing view
#view: 3
#flip_alt_rows: false

# Optional banner image (relative to `assets/media/` folder).
#banner:
#  caption: ''
#  image: ''


sections:
  - block: portfolio
    #id: proj1
    content:
      title: research
      text: 
      #  test
      #  {{< figure src="coders.jpg" caption="A caption" numbered="true" >}}
      #filters:
      #  folders:
      #    - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      #default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
      #  - name: Deep Learning
      #    tag: Deep Learning
      #  - name: Other
      #    tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      #columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false

---

<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-9M5LBVNQ1R"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-9M5LBVNQ1R');
</script>


<p style="margin-top: 0px; text-align: justify;"> Our research lab focuses on developing theoretical and computational methods to study biological processes across different temporal and spatial scales. We integrate physics, multiscale simulations, and machine learning to unravel the mechanisms of essential biological machineries and design molecules for treating related diseases. We strive to build a diverse team, bringing together a wide range of backgrounds and expertise.
</p>
<div style="margin-bottom: 80px;"></div>


<h3 style="margin-bottom: 0px;">Multiscale modeling and simulations of biological machineries</h3>
<div style="display: flex; align-items: center;">
    <div style="margin-top: 0px;">
        {{< figure src="model_scales.png" width="2000px" height="auto" caption="" numbered="false" >}}
    </div>
    <div style="margin-left: 20px;">
        <p style="margin-top: 0px; text-align: justify;"> Our lab focuses on developing and applying multiscale modeling methods to connect molecular biology with systems biology, harnessing the power of modern computational physics. For example, we are building a multiscale model that characterizes how small changes in contractile proteins impact cardiac sarcomere function, based on our previous work (<a href="https://www.pnas.org/doi/abs/10.1073/pnas.2215836120">PNAS 2023</a>, <a href="https://academic.oup.com/pnasnexus/article/3/8/pgae279/7714041">PNAS Nexus 2024</a>)
        </p>
    </div>
</div>

<div style="margin-bottom: 80px;"></div>


<h3 style="margin-bottom: 0px;">Applying deep learning and statistical physics to reveal protein conformations and functions</h3>
<div style="display: flex; align-items: center;">
    <div style="margin-top: 0px;">
        {{< figure src="sm_ai_pmf.png" width="5000px" height="auto" caption="" numbered="false" >}}
    </div>
    <div style="margin-left: 20px;">
        <p style="margin-top: 0px; text-align: justify;"> 
        Molecular simulations have become a valuable complement to laboratory and clinical studies in combating various diseases. We are interested in applying statistical physics and deep learning to extend the limited timescales that conventional molecular simulations are able to cover.
        Previously, we employed rare-event sampling techniques to search for the most probable transition pathways for molecular motor actions (<a href="https://pubs.acs.org/doi/abs/10.1021/ja512605w">JACS 2015</a>, <a href="https://elifesciences.org/articles/34186">eLife 2018</a>).
        </p>
    </div>
</div>

<div style="margin-bottom: 80px;"></div>

<h3 style="margin-bottom: 0px;">Drug discovery inspired by multiscale simulations</h3>
<div style="display: flex; align-items: center;">
    <div style="margin-top: 0px;">
        {{< figure src="drug_discovery.png" width="2000px" height="auto" caption="" numbered="false" >}}
    </div>
    <div style="margin-left: 20px;">
        <p style="margin-top: 0px; text-align: justify;"> Taking advantage of the conformational ensembles obtained from the aforementioned simulations, we discover potential drug binding sites and screen allosteric modulators with the assistance of machine learning. We are currently designing small molecules targeting cardiac myosin (for cardiomyopathy) and LRRK2 (for Parkinson's disease, <a href="https://pubs.acs.org/doi/full/10.1021/acschembio.2c00868">ACS Chem Biol 2023</a> and <a href="https://www.nature.com/articles/s41421-023-00639-8">Cell Discovery 2024</a>).
        </p>
    </div>
</div>
