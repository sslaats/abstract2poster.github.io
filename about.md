---
layout: default
title: poster
---
<h1>{% include abstract/title.md %}</h1>

{% capture introduction %}
{% include abstract/introduction.md %}
{% endcapture %}

{% capture methods %}
{% include abstract/methods.md %}
{% endcapture %}

{% capture results %}
{% include abstract/results.md %}
{% endcapture %}

{% capture conclusion %}
{% include abstract/conclusion.md %}
{% endcapture %}

{% include sections.html %}