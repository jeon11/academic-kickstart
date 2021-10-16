+++
# Slider widget.
widget = "slider"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = false  # Activate this widget? true/false
weight = 1  # Order that this section will appear.

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = '18000'  # 18000

# Slide height (optional).
# E.g. `500px` for 500 pixels or `calc(100vh - 70px)` for full screen.
height = "calc(100vh - 100px)" #calc(100vh - 70px)

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = "👋 Hello, I'm Jin!"
  content = "<br>I'm a graduate student at the Human Centered Design and Engineering (HCDE) program at the University of Washington.<br><br>I'm a **data enthusiast** passionate in **UX research**.<br>I am inquisitive 🧐, empathetic ❤️, and data-driven 📊. <br><br>"
  align = "right"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  overlay_color = "#B5CEEF"  # An HTML color value.
  overlay_img = "uxr_10fr184.gif"  # uxr_10fr184.gif Image path relative to your `static/img/` folder.  uxr_10fr184.gif
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  cta_label = "See My Projects"
  cta_url = "#projects"
  cta_icon_pack = "fab"
  cta_icon = ""

  [cta_alt]
    url = "#about"
    label = "More About Me"
  cta_alt = "See me "

[[item]]
  title = "<mark>**Latest Project - SAP** </mark>"
  content = "<br>As an initiative to integrate user research into the design process and establish a UX framework library so that design decisions are informed and inspired by user data. <br><br> As a UX researcher, I spearheaded a generative study to identify user needs and pain points, and visualize them through journey maps.<br><br>"
  align = "left"

  overlay_color = "#B5CEEF"  # An HTML color value.
  overlay_img = "slider2.png"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.7  # Darken the image. Value in range 0-1.

  cta_label = "Read More"
  cta_url = "./project/sap/"
  # cta_icon_pack = "fas"
  # cta_icon = ""
[design.background]

  # Background gradient.
  gradient_start = "#CE87C1" #"#CE87C1"
  gradient_end = "#B5CEEF" # "#B5CEEF"
+++

<!-- [[item]]
  title = "Right"
  content = "I am right aligned :smile:"
  align = "right"

  overlay_color = "#333"  # An HTML color value.
  overlay_img = ""  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1. -->
