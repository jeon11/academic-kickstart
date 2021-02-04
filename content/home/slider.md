+++
# Slider widget.
widget = "slider"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 1  # Order that this section will appear.

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = 'false'  # 7000

# Slide height (optional).
# E.g. `500px` for 500 pixels or `calc(100vh - 70px)` for full screen.
height = "calc(100vh - 70px)"

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = "👋 Hello, I'm Jin!"
  content = "<br>I'm a graduate student at the Human Centered Design and Engineering (HCDE) program at the University of Washington.<br><br>I'm a **data enthusiast** passionate in <mark>**UX research**</mark>. <br>I'm curious 🧐, data-driven 📊, and empathetic ❤️. <br><br><u>[• More About Me](#about)</u><br><u>[• See My Projects](#projects)</u>"
  align = "right"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  overlay_color = "#B5CEEF"  # An HTML color value.
  overlay_img = "uxr_8frpersecond.gif"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.2  # Darken the image. Value in range 0-1.

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  # cta_label = "Go to About Me"
  # cta_url = "#about"
  # cta_icon_pack = "fas"
  # cta_icon = "user"

[[item]]
  title = "Project Highlights"
  content = "<a href='#projects'> See my projects</a> :smile: <iframe width='760' height='600' src='https://editor.p5js.org/jeon11/embed/rIpX6_wm0' frameborder='0'></iframe>"
  align = "left"

  overlay_color = "#B5CEEF"  # An HTML color value.
  overlay_img = "<iframe src='https://editor.p5js.org/jeon11/embed/rIpX6_wm0'></iframe>"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.


+++

<!-- [[item]]
  title = "Right"
  content = "I am right aligned :smile:"
  align = "right"

  overlay_color = "#333"  # An HTML color value.
  overlay_img = ""  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1. -->
