---
name: HW6
tools: [Python, Altair, vega-lite]
image: assets/pngs/viz1.png
description: HW6 Submission
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# HW6

## Visualization 1: Building and Agency Bar Graph

<vegachart schema-url="{{ site.baseurl }}/assets/json/viz1.json" style="width: 100%"></vegachart>


## Visualization 2:


<!-- these are written in a combo of html and liquid --> 

<div class="left">
{% include elements/button.html link="https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_data/main/building_inventory.csv" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/QUA605/qua605.github.io/blob/main/python_notebooks/hw6.ipynb" text="The Analysis" %}
</div>