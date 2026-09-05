---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html number=forloop.index %}
{% endfor %}

<hr>

{% assign next_publication_number = site.publications.size | plus: 1 %}

# Working papers
## {{ next_publication_number }}. Food on Road: A Novel County-Level Analysis of Road Density and its Impact on Food Prices in the U.S. Market, with Dr. Jasmine (Aichih) Chang, Dr. Jim Shi
{% assign next_publication_number = next_publication_number | plus: 1 %}
<details class="publication-abstract">
<summary>Abstract</summary>

**Abstract**: Food crisis has been prevailing for decades. Recently, the world-wide economic inflation, especially in food price, has exacerbated the food crisis dramatically. This study examines how transportation infrastructure, e.g., road density, influences food price through the lens of food access and mobility. Using 2010 and 2020 U.S. county-level datasets in conjunction with other data sources, empirically we reveal that, in the U.S. market, higher road density significantly reduces cost per meal by enhancing local and regional food mobility. In particular, ceteris paribus, one mile per square mile increase in road density reduces the cost per meal by 1.3%. We further reveal that road density helps narrow price disparities tied to store availability, while such price dampening effect diminishes or vanishes in or near densely populated areas. These findings shed light on how infrastructure influences food mobility and price equity, and offer evidence-based implications for urban planners, transportation policymakers, and local governments. This study makes several salient contributions to the extant literature. First, it documents empirical evidence from the U.S. market on how infrastructure affects food prices, along with other geographic, demographic, and temporal factors. Second, the study offers a nuanced and deep understanding of how transportation networks interact with local food market, spatially and temporally. Last but not least, this study enriches the food-transportation literature with novel empirical evidence by curating a county-level road density dataset.
 </details>

## {{ next_publication_number }}. Enhancing Resilience in Local Food Systems through LLM-Based Multi-Agent Decision Support for Adaptive Coordination, with Dr. Wenbo Wang, Qin Liu, Dr. Jasmine (Aichih) Chang, Dr. Jim Shi.
{% assign next_publication_number = next_publication_number | plus: 1 %}
<details class="publication-abstract">
<summary>Abstract</summary>

**Abstract**:  We propose a multi-agent coordination framework for resilient local food systems, where autonomous agents collaboratively detect disruptions, assess operational impacts, reallocate orders, replan logistics, and negotiate recovery actions under distributed information. This framework allows a food hub and its ecosystem partners to autonomously coordinate recovery actions after disruptions through privacy-preserving negotiation and adaptive decision-making, while balancing service reliability, food waste reduction, and fairness.
 </details>


<hr>

# Work in progress
## {{ next_publication_number }}. Ripple Effects of Tariff Shocks: Estimating Supply Chain Disruptions and Transportation Cost Spillovers in the U.S. Tomato Market, with Dr. Jasmine (Aichih) Chang, Dr. Jim Shi
{% assign next_publication_number = next_publication_number | plus: 1 %}
<details class="publication-abstract">
<summary>Abstract</summary>

**Abstract**: This study investigates the indirect effects of import tariffs on food prices, with a focus on the U.S. tomato market. Specifically, it examines how policy-induced tariff shocks affect prices through the transportation channel. Employing a Difference-in-Differences (DiD) approach, the analysis identifies the causal relationship between tariff changes and food prices. Furthermore, the study develops a U.S. tomato transportation network model to estimate the resulting shifts in transportation costs, providing insights into the broader economic consequences of trade policy.
 </details>

## {{ next_publication_number }}. Integrating AI-Powered XR Wearables for Real-Time Shelf-Life Estimation and Pricing Optimization, with Dr. Jasmine (Aichih) Chang
{% assign next_publication_number = next_publication_number | plus: 1 %}
<details class="publication-abstract">
<summary>Abstract</summary>

**Abstract**: Fresh food retailers operate in a highly uncertain environment where product perishability and fluctuating consumer demand make pricing and inventory management especially challenging. This project proposes an AI-enabled dynamic pricing system using XR wearables to track freshness and adjust prices in real time. By linking fixed purchase costs with prices shaped by perishability and fluctuating demand, retailers can optimize product selection, ordering, and pricing. The approach aims to boost profitability, reduce waste, and improve decision-making in fresh food retail.
 </details>

## {{ next_publication_number }}. The Impact and Implications of Bag Tax Policies on Sustainable Operations: A Systems Dynamics Approach, with Dr. Nesreen El-Rayes, Dr. Jasmine (Aichih) Chang, Dr. Jim Shi
<details class="publication-abstract">
<summary>Abstract</summary>

**Abstract**: This study investigates the impact of bag tax policy in the United States. By leveraging 71k historical dataset and Vensim modeling, we simulate the interactions and feedback loops to demonstrate and forecast policy impacts, providing evidence-based recommendations for optimizing tax structures and accompanying measures to maximize environmental and social benefits.
 </details>