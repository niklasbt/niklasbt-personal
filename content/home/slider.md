+++
# Slider widget.
widget = "slider"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 1  # Order that this section will appear.

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = 5000

# Slide height (optional).
# E.g. `500px` for 500 pixels or `calc(100vh - 70px)` for full screen.
height = "calc(100vh - 70px)"

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = ""
  content = ""
  align = "right"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  overlay_color = "#666"  # An HTML color value.
  overlay_img = "slider_1.png"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  cta_label = "About"
  cta_url = "#about"
  cta_icon_pack = "fas"
  cta_icon = "user-circle"

[[item]]
  title = ""
  content = ""
  align = "right"

  overlay_color = "#555"  # An HTML color value.
  overlay_img = "slider_2.png"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.
  
  cta_label = "Publications"
  cta_url = "publication/"
  cta_icon_pack = "fas"
  cta_icon = "book"

[[item]]
  title = ""
  content = ""
  align = "right"

  overlay_color = "#333"  # An HTML color value.
  overlay_img = "slider_3.png"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.
  
  cta_label = "Contact"
  cta_url = "contact/"
  cta_icon_pack = "fas"
  cta_icon = "envelope"
  
+++
