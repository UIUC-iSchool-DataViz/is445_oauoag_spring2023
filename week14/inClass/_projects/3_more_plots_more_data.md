---
name: More with Altair
tools: [Python, HTML, vega-lite, Altair]
image: assets/pngs/manyplotsaltair.png
description: Even more plots with Altair.
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# More Altair Plots

## Simple line plot with "for free" interactivity
First a "simple" line plot with Altair:

<vegachart schema-url="{{ site.baseurl }}/assets/json/buildings_sqrt.json" style="width: 100%"></vegachart>

## "Melting" the data for more complex plos

<vegachart schema-url="{{ site.baseurl }}/assets/json/buildings_tooltip.json" style="width: 100%"></vegachart>

## Adding a dropdown interactive

<vegachart schema-url="{{ site.baseurl }}/assets/json/buildings_dropdown.json" style="width: 100%"></vegachart>


<!-- these are written in a combo of html and liquid --> 

<div class="left">
{% include elements/button.html link="https://github.com/UIUC-iSchool-DataViz/is445_data/raw/main/building_inventory.csv" text="The Data" %}
</div>


<div class="right">
{% include elements/button.html link="https://github.com/UIUC-iSchool-DataViz/is445_oauoag_spring2023/blob/main/week13/inClass_week13.ipynb" text="The Analysis" %}
</div>

