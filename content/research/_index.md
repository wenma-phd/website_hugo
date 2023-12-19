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

# Proj1
<div style="display: flex; align-items: center;">
    <div>
        {{< figure src="coders.jpg" width="500px" height="auto" caption="" numbered="false" >}}
    </div>
    <div style="margin-left: 20px;">
        <p> style="font-weight: bold;"> Multiscale modeling of biological machineries
        </p>
        Our group focus on developing and applying multiscale modeling methods to connect molecular biology to systems biology. For example, we are trying to build a multiscale model that links small changes in contractile proteins to muscle function, based on our previous work (PNAS 2023 {{< cite="/publication/ma-2023-integrating" view="citation" >}}, bioRxiv 2023 {{< cite= "/publication/bodt-2023-dilated" view="citation" >}})
        
    </div>
</div>

<div style="margin-bottom: 50px;"></div>

# Proj2
<div style="display: flex; align-items: center;">
    <div>
        {{< figure src="coders.jpg" width="500px" height="auto" caption="" numbered="false" >}}
    </div>
    <div style="margin-left: 20px;">
        <p>Your description here...</p>
    </div>
</div>


<div style="display: flex; align-items: center;">
    <div>
        {{< figure src="coders.jpg" width="500px" height="auto" caption="" numbered="false" >}}
    </div>
    <div style="margin-left: 20px;">
        <p>Your description here...</p>
    </div>
</div>
