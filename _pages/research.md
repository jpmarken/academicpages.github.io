---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "images/profile.png"
---
One of the central challenges associated with translating synthetic biology advances in the laboratory into real-world applications is the fact that the environmental conditions that cells experience in a deployment context are different from those in the laboratory, often leading to unreliable system performance and outright system failure. This is particularly true when addressing sustainability applications, which will require the deployment of microbes into diverse environments such as agricultural soils, living materials, and water-treatment plants.

The goal of my research program is to uncover the principles by which environmental conditions impact the performance of genetic circuits, and to develop engineering strategies to ensure their reliable and predictable performance across environmental contexts.

<p align='center'>
<img src='/images/EnvPhysBehavior.png' width='600'>
</p>

My current projects falls under three main categories: experimental work studying the principles of microbial gene expression under different physiological states, theoretical work developing new ways to analyze biomolecular system behavior, and application-driven work developing methods to better understand and engineer the rhizosphere microbiome. More details on each of these areas can be found below.

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %} {% include archive-single.html type="grid" %} {% endfor %}
