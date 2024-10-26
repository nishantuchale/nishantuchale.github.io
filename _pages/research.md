---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  image: gfd.png
  caption: "[Goddard Space Flight Center (GSFC)-NASA](https://svs.gsfc.nasa.gov/vis/a030000/a030000/a030017/frames/4000x2000_2x1_30p/rad/)"
  
---
I am broadly interested in the profound interactions and the interconnected dynamics between our Earth's atmosphere and oceans shaping our weather and climate

I have worked under Dr. Bhupendra Singh at the [Centre for Climate Change and Research](http://cccr.tropmet.res.in/home/index.jsp) since July 2022 on projects related to precipitation extremes and exploring its chaging dynamics in a warmer climate.

Later I have worked under Prof. Vishal Dixit at the [Monsoon Dynamics Lab](https://www.climate.iitb.ac.in/?page_id=8368) in IIT Bombay since Aug 2023 to Jan 2024 on developing a relationship between near-surface air temperature and humidity and understand the mechanism leading to temperature extremes.

Further, I have also joined the GFD group at ICTS-TIFR since Feb 2024 where I am working on understanding the energy flow pathways in the internal wave continuum in oceans. My work is supported by the Long--Term Visiting Student Rsearch Fellowship.

# Publications
1. Uchale, N. N. & Singh, B. B. (2024) Characteristics and projected changes in maximum daily precipitation across the
globe. Conditionally accepted in QJRMS
2. Singh, B. B. & Uchale, N. N. (2025) Changing temporal and spatial distribution of precipitation extremes over the
globe in a warmer climate. In prep
<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
