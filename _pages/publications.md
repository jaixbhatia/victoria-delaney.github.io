---
layout: page
permalink: /publications/
title: peer-reviewed publications
description:
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->
{% include bib_search.liquid %}

<div class="publications">
  {% bibliography --group_by type %}
</div>
