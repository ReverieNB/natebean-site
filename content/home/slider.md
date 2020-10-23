+++
# Slider widget.
widget = "slider"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 70 # Order that this section will appear.

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = false

# Slide height (optional).
# E.g. `500px` for 500 pixels or `calc(100vh - 70px)` for full screen.
height = ""

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = "Jared Goff's Reliance on Short Passing"
  content = "Analysis of Jared Goff's first 5 games"
  align = "center"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  overlay_color = "#34a4eb"
  overlay_img = "headers/rams_header.png" 
  overlay_filter = 0  

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  cta_label = "Read Now"
  cta_url = "http://127.0.0.1:4321/post/placeholder/"
  cta_icon_pack = ""
  cta_icon = ""

[[item]]
  title = "Follow Twitter"
  content = "For New Posts"
  align = "center"
  
  cta_label = "@FakeNateBean"
  cta_url = "https://twitter.com/FakeNateBean"

  overlay_color = "#003594"
  overlay_img = "headers/rams_header.png" 
  overlay_filter = 0

#[[item]]
#  title = "Coming Soon"
#  content = ""
#  align = "center"
#
#  overlay_color = "#333"  # An HTML color value.
#  overlay_img = ""  # Image path relative to your `static/media/` folder.
#  overlay_filter = 0.5  # Darken the image. Value in range 0-1.
+++
