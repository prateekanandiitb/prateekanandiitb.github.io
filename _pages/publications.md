---
layout: page
title: "Publications"
permalink: /publications/
sidebar: true
---

# Publications

Below is an automatically generated list of our group’s publications.  
You can update them in `_data/publications.yml` — no need to edit this page again.

---

<div style="max-width:800px; margin:auto;">

{% assign pubs = site.data.publications | sort: 'year' | reverse %}
{% for paper in pubs %}
<div style="margin-bottom:1.2rem; padding-left:0.2rem;">
  <strong>{{ paper.title }}</strong><br>
  {{ paper.authors }}<br>
  <em>{{ paper.journal }}</em>, {{ paper.year }}
  {% if paper.doi %} · <a href="{{ paper.doi }}" target="_blank">DOI</a>{% endif %}
  {% if paper.link %} · <a href="{{ paper.link }}" target="_blank">Link</a>{% endif %}
  {% if paper.note %}<br><small><em>{{ paper.note }}</em></small>{% endif %}
</div>
{% endfor %}

</div>
