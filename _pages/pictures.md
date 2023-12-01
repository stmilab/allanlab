---
title: "STMI Lab - Pictures"
layout: piclay
excerpt: "STMI Lab -- Pictures"
permalink: /pictures/
---

# Pictures

## Table of Contents

- [Pictures](#pictures)
  - [Table of Contents](#table-of-contents)
  - [Conference Travel](#conference-travel)
  - [Graduation](#graduation)
  - [Lab Retreat](#lab-retreat)

## Conference Travel

{% assign number_printed = 0 %}
{% for pic in site.data.pictures %}

{% assign even_odd = number_printed | modulo: 4 %}

{% if even_odd == 0 %}

<div class="row">
{% endif %}
{% if pic.occasion == "travel" %}
<div class="col-sm-3 clearfix">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/Gallery/{{ pic.image }}" class="img-responsive" width="95%" style="float: left" />
</div>
{% endif %}
{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd > 2 %}

</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 4 %}
{% if even_odd == 1 %}

</div>
{% endif %}

{% if even_odd == 2 %}

</div>
{% endif %}

{% if even_odd == 3 %}

</div>
{% endif %}

<p> &nbsp; </p>

## Graduation

{% assign number_printed = 0 %}
{% for pic in site.data.pictures %}

{% assign even_odd = number_printed | modulo: 4 %}

{% if even_odd == 0 %}

<div class="row">
{% endif %}
{% if pic.occasion == "graduation" %}
<div class="col-sm-3 clearfix">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/Gallery/{{ pic.image }}" class="img-responsive" width="95%" style="float: left" />
</div>
{% assign number_printed = number_printed | plus: 1 %}
{% endif %}
{% if even_odd > 2 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 4 %}
{% if even_odd == 1 %}

</div>
{% endif %}

{% if even_odd == 2 %}

</div>
{% endif %}

{% if even_odd == 3 %}

</div>
{% endif %}

<p> &nbsp; </p>

## Lab Retreat

{% assign number_printed = 0 %}
{% for pic in site.data.pictures %}

{% assign even_odd = number_printed | modulo: 4 %}

{% if even_odd == 0 %}

<div class="row">
{% endif %}
{% if pic.occasion == "causal" %}
<div class="col-sm-3 clearfix">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/Gallery/{{ pic.image }}" class="img-responsive" width="95%" style="float: left" />
</div>
{% endif %}
{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd > 2 %}

</div>
{% endif %}
{% endfor %}

{% assign even_odd = number_printed | modulo: 4 %}
{% if even_odd == 1 %}

</div>
{% endif %}

{% if even_odd == 2 %}

</div>
{% endif %}

{% if even_odd == 3 %}

</div>
{% endif %}

<p> &nbsp; </p>
