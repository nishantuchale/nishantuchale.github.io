---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  image: gfd.png
  caption: "[Goddard Space Flight Center (GSFC)-NASA](https://svs.gsfc.nasa.gov/vis/a030000/a030000/a030017/frames/4000x2000_2x1_30p/rad/)"
  
---

My academic research falls into two main areas: understanding the influence of
geography on actor behavior before, during, and after civil conflict, and
developing new tools to improve the study of institutions (both formal and
informal) in peace and conflict. One strand of research in this first area
explores how the territories that ethnic groups inhabit shape rebel group
formation and condition their relationship with the state. My interest in
geography also informs projects on active conflicts including the targeting of
UN peacekeepers by insurgent groups, civilian victimization after rebel
territorial conquest, and communal violence in fragile settings.

My other main research agenda uses advanced methods to develop new measures of
institutions. One project uses Bayesian item response theory to measure the
strength of peace agreements as a latent variable and free researchers from
post-treatment bias caused by using the duration of agreements as a proxy for
their strength. In others, I apply unsupervised learning techniques to over a
billion observations of product-level international trade data to measure
economic interdependence and illicit economic exchange.

In a new avenue of research, I leverage social media data to explore
participation in extremist movements across multiple contexts, gaining insight
into the early stages of radicalization.

title: "Publications"
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
