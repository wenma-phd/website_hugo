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
      text: |
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
<div style="margin-bottom: 80px;"></div>

<h3 style="margin-bottom: 0px;">Multiscale modeling of biological machineries</h3>
<div style="display: flex; align-items: center;">
    <div>
        {{< figure src="model_scales.png" width="1800px" height="auto" caption="" numbered="false" >}}
    </div>
    <div style="margin-left: 10px;">
        <p style="margin-top: 0px;"> Our group focus on developing and applying multiscale modeling methods to connect molecular biology to systems biology. For example, we are trying to build a multiscale model that links small changes in contractile proteins to cardiac muscle function, based on our previous work (<a href="https://www.pnas.org/doi/abs/10.1073/pnas.2215836120" target="_blank">PNAS 2023</a>, <a href="https://www.biorxiv.org/content/10.1101/2023.11.10.566646.abstract" target="_blank">bioRxiv 2023</a>).
        </p>
    </div>
</div>

<div style="margin-bottom: 80px;"></div>

<h3 style="margin-bottom: 0px;">Applying machine learning and statistical physics to reveal protein conformations and functions</h3>
<div style="display: flex; align-items: center;">
    <div>
        {{< figure src="sm_ai_pmf.png" width="5000px" height="auto" caption="" numbered="false" >}}
    </div>
    <div style="margin-left: 10px;">
        <p style="margin-top: 0px;"> Remarkable advances in life science now permit in-silico exploration of a vast range of length scales from single-protein systems to cell-scale organization and dynamics. We are interested to apply statistical physics and machine learning to extend the timescale conventional methods can simulate. For example, we have employed rare-event sampling techniques to search for the most probable transition pathways for molecular motor actions (<a href="https://pubs.acs.org/doi/abs/10.1021/ja512605w" target="_blank">JACS 2015</a>, <a href="https://elifesciences.org/articles/34186" target="_blank">eLife 2018</a>).
        </p>
    </div>
</div>

<div style="margin-bottom: 80px;"></div>

<h3 style="margin-bottom: 0px;">Simulation inspired drug discovery</h3>
<div style="display: flex; align-items: center;">
    <div>
        {{< figure src="drug_discovery.png" width="1000px" height="auto" caption="" numbered="false" >}}
    </div>
    <div style="margin-left: 10px;">
        <p style="margin-top: 0px;"> Taking advantage of the conformational ensembles from molecular simulations, we discover potential drug binding sites and screen allosteric modulators with the help from machine learning. We are currently designing small molecules targeting myosin (cardiomyopathy) and LRRK2 (Parkinson's disease) (<a href=” https://pubs.acs.org/doi/full/10.1021/acschembio.2c00868" target="_blank">ACS Chem Biol</a>).
        </p>
    </div>
</div>
