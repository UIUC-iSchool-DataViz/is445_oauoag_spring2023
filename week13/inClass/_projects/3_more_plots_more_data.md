---
name: More with Altair
tools: [Python, HTML, vega-lite, Altair]
image: assets/pngs/vegalitemanyways.png
description: Even more plots with Altair.
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# More Altair Plots

First a "simple" line plot with Altair:

<vegachart schema-url="{{ site.baseurl }}/assets/json/buildings_stats1.json" style="width: 100%"></vegachart>






<!-- these are written in a combo of html and liquid --> 

<div class="left">
{% include elements/button.html link="https://github.com/UIUC-iSchool-DataViz/is445_data/raw/main/building_inventory.csv" text="The Data" %}
</div>


<div class="right">
{% include elements/button.html link="https://github.com/jnaiman/online_cv_public/blob/main/python_notebooks/test_generate_plots.ipynb" text="The Analysis" %}
</div>

