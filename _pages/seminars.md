---
title: "t~ai - Seminars"
layout: gridlay
excerpt: "Seminars."
sitemap: false
permalink: /seminars/
---

## Seminars

### Highlights

{% assign number_printed = 0 %}
{% for publi in site.data.seminars %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if publi.highlight == 1 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
 <div class="well">
  <pubtit>{{ publi.title }}</pubtit>
  <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="33%" style="float: left" />
  <p><em>{{ publi.authors }}</em></p>
  <p><strong><a href="{{ publi.url }}">{{ publi.display }}</a></strong></p>
  <p><strong><a href="{{ publi.video}}">YouTube Video</a></strong></p>
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

 
### Full List 

[Articles, Preprints, and Conference Proceedings ](https://research.unsw.edu.au/people/dr-rohitash-chandra/publications)

{% for publi in site.data.seminars %}

  {{ publi.title }} <br />
  <em>{{ publi.authors }}</em><br/>
  <strong><a href="{{ publi.url }}">{{ publi.display }}</a></strong><br/>
  <strong><a href="{{ publi.video}}">YouTube Video</a></strong>

{% endfor %}

