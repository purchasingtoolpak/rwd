---
title: Jekyll Slider
image_sliders:
  - slider1
---

<html>
  <head>
    <!-- Slider CSS -->

    {% include head.html %}

  </head>

  <body>
    <h2><center> here is the slider</center></h2>
    <div id="wrapper">
      {% include slider.html selector="slider1" %}
    </div>
      {% include slider_scripts.html %}
  </body>
</html>
