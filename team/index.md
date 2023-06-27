---
title: Team
redirect_from:
  - /lab-members
  - /alums
  - /mascots
  - /staff
  - /trainees
---

# <i class="fas fa-users"></i>

## Current Members

Our a team focused on the development of the datasets, algorithms and statistical inference 
methods for analyzing Image, Video and Text data.  We are always looking for motivated and passionate students to join us.  If you're interested in 
the work we're doing, please reach out!

{% capture html %}
{% include team-list.html role="pi" group="current" %}
{% include team-list.html role="postdoc" group="current" %}
{% include team-list.html role="phd" group="current" %}
{% include team-list.html role="undergrad" group="current" %}
{% include team-list.html role="programmer" group="current" %}
{% include team-list.html role="mascot" group="current" %}
{% endcapture %}

{% include centerer.html html=html %}

<!-- section break -->

## Alumni

We are incredibly proud of all of the COMBINE-lab alumni who have passed through the lab, for whatever period of time they were with us. Below
is a list of lab alumni (if you feel you're missing from the list and would like to be added, please e-mail us):

{% capture html %}
{% include team-list.html role="pi" group="alum" mini="true" %}
{% include team-list.html role="phd_g" group="alum" mini="true" %}
{% include team-list.html role="undergrad" group="alum" mini="true" %}
{% endcapture %}

{% include centerer.html html=html %}
