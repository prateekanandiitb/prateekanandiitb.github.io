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
<h2 style="font-weight:700; margin-top:2rem;">Journal Articles</h2>
{% bibliography --query @article or @inproceedings %}

<h2 style="font-weight:700; margin-top:2rem;">Ph.D. Thesis</h2>
{% bibliography --query @phdthesis %}

</div>
