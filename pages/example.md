---
title: Example Page
nav: Example
nav_order: 1
leaflet-viewer: true 
---

Write page content in Markdown.
Add annotated images and maps using the "leaflet-item.html" include!

## Image Example

`{% raw %}{% include leaflet-item.html annotation="Jan_Brueghel_Snowy_Landscape-annotations.json" %}{% endraw %}`

{% include leaflet-item.html annotation="Jan_Brueghel_Snowy_Landscape-annotations.json" %}

## Map Example

`{% raw %}{% include leaflet-item.html annotation="brueghel_map-annotations.json" %}{% endraw %}`

{% include leaflet-item.html annotation="brueghel_map-annotations.json" %}
