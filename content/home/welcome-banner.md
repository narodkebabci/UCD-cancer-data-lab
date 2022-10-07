---
widget: blank 
headless: true 
active: true
weight: 10

title: ''

design:
  columns: '1'
  background:
    color: '#f7f7f7'
#    gradient_start: '#1565c0'
#    gradient_end: '#15bbc0'
#    gradient_angle: 90
#    text_color_light: true

advanced:
  css_class: align-items-center
  
---

<div>
  {{ $image := .Resources.GetMatch "media/icon.png" }}
  <img src="{{ $image.RelPermalink }}" style="margin: 0 0 0 15px; float: right;" width="{{ $image.Width }}" height="{{ $image.Height }}">
  <p style="text-align: justify;">The UCD Cancer Data Lab, led by <a href="https://cancerdata.ucd.ie/author/colmjryan/"> Dr. Colm J. Ryan </a>, use large-scale data analysis to understand how genetic variation in cancer alters molecular interaction networks and to identify ways to target these alterations therapeutically.</p>
</div>

