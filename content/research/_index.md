---
Title: Research

#gallery_item:
#   - album: assets/media/album/
#       image: coders.jpg
#       caption: Write your image 1 caption here

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
        test
        {{< figure src="coders.jpg" caption="A caption" numbered="true" >}}

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

{{< figure src="coders.jpg" width="400px" height="auto" caption="" numbered="false" class="align-left" >}}
<div style="margin-left: 30px;">
  <p>Your description here</p>
</div>
