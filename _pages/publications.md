---
title: "STMI Lab - Publications"
layout: gridlay
excerpt: "STMI Lab -- Publications."
sitemap: false
permalink: /publications/
---

# Publications

(For a full list of publications and patents see [below](#journal-papers) or go to [Google Scholar](https://scholar.google.ch/citations?user=TOAg4GkAAAAJ), [GitHub](https://github.com/stmilab))

## Table of Contents

- [Publications](#publications)
  - [Table of Contents](#table-of-contents)
  - [Group highlights](#group-highlights)
  - [Journal Papers](#journal-papers)
  - [Conference Papers](#conference-papers)
  - [Patents](#patents)

## Group highlights

{% assign number_printed = 0 %}
{% for publi in site.data.publist %}

{% assign even_odd = number_printed | modulo: 2 %}

<!-- We only keep the first 4 highlighted articles -->

{%if number_printed >= 4%}
{% break %}
{% endif %}
{% if publi.highlight == 1%}

{% if even_odd == 0 %}

<div class="row">
{% endif %}
<div class="col-sm-6 clearfix">
 <div class="well">
  <pubtit>{{ publi.title }}</pubtit>
  <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="50%" style="float: left" />
  <pubdesc>{{ publi.description }}</pubdesc>
  <p><em>{{ publi.authors }}</em></p>
  <p><strong><a href="{{ publi.link.url }}">{{ publi.link.display }}</a></strong></p>
  <p class="text-danger"><strong> {{ publi.news1 }}</strong></p>
  <p><b>{{ publi.news2 }}</b></p>
 </div>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}

</div>
{% endif %}

{% endif %}
{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}

</div>
{% endif %}

<p> &nbsp; </p>

## Journal Papers

{% assign i = 1 %}
{% for publi in site.data.publist %}

{% if publi.journal == 1 %}
**\[J{{i}}\]** {{ publi.title }} <br />
<em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
{% assign i = i | plus: 1 %}
{% endif %}

{% endfor %}

## Conference Papers

{% assign i = 1 %}
{% for publi in site.data.publist %}

{% if publi.conference == 1 %}

**\[C{{i}}\]** {{ publi.title }} <br />
<em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }} </a>
{% if publi.news2 %}**{{publi.news2}}**{% endif %}
{% assign i = i | plus: 1 %}
{% endif %}

{% endfor %}

<!-- ## Workshops/Demos/Abstracts/Posters

{% for publi in site.data.publist %}

  {% if publi.workshop == 1 %}

  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

  {% endif %}

{% endfor %} -->

## Patents

{% assign i = 1 %}
{% for publi in site.data.publist %}

{% if publi.patent == 1 %}

**\[P{{i}}\]** {{ publi.title }} <br />
<em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
{% assign i = i | plus: 1 %}
{% endif %}

{% endfor %}
