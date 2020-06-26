---
layout: archive-without-title
title: "Projects"
permalink: /projects/
---

<h1>Medical</h1>
<div class="grid__wrapper">
  {% for project in site.projects %}
      {% if project.domain == "Medical" %}
        {% include archive-project.html type="grid" %}
      {% endif %}
  {% endfor %}
</div>

<!-- Do not remove -->
<div style="clear:both;"></div>
<!-- Do not remove -->

<h1>Theoretical</h1>
<div class="grid__wrapper">
  {% for project in site.projects %}
      {% if project.domain == "Theoretical" %}
        {% include archive-project.html type="grid" %}
      {% endif %}
  {% endfor %}
</div>

<!-- Do not remove -->
<div style="clear:both;"></div>
<!-- Do not remove -->

<h1>Philosophical</h1>
<div class="grid__wrapper">
    {% for project in site.projects %}
        {% if project.domain == "Philosophical" %}
          {% include archive-project.html type="grid" %}
        {% endif %}
    {% endfor %}
</div>

<!-- Do not remove -->
<div style="clear:both;"></div>
<!-- Do not remove -->


<h1>Funders</h1>
<div class="grid_wrapper">
{% for post in site.data.funders %}
    {% include archive-founder.html type="grid" %}
{% endfor %}
</div>