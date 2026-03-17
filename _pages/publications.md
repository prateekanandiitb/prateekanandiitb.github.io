---
layout: page
permalink: /publications/
title: Publications
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">
## Journal & Conference Publications
{% bibliography --query @article or @inproceedings %}

## Thesis
{% bibliography --query @phdthesis %}

</div>
