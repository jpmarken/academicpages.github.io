---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "images/profile.png"
---
One of the central challenges associated with translating synthetic biology advances in the laboratory into real-world applications is the fact that the environmental conditions that cells experience in a deployment context are different from those in the laboratory. This is particularly true when addressing sustainability applications, where many will require the deployment of microbes into diverse environments such as agricultural soils, living materials, and water-treatment plants.

The goal of my research program is to discover and develop new engineering principles to help develop a rigorous foundation for successfully translating synthetic biology advances in the laboratory into their deployment environments. Major research questions in this direction include:

- How do environmental conditions affect microbial physiology, and thereby affect the performance of genetic circuits?
- How do we design genetic circuits to perform consistently across different strain backgrounds and physiological states?
- How do we monitor microbial activity in difficult-to-access environments like the soil?
- How do we ensure the reliable and safe performance of engineered microbial systems that might be inaccessible after deployment?

I address these questions using an interdisciplinary approach that merges both theoretical and experimental techniques. 

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %} {% include archive-single.html type="grid" %} {% endfor %}
