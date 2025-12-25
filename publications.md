---
layout: sub
title: Publications
---
# Publications

## Refereed Conferences

{% for pub in site.data.conference %}
1. [{{ pub.name }}]({{ pub.url }})\
   *{{ pub.authors }}*\
   *{{ pub.conf }}*
{% endfor %}

## Journals

{% for pub in site.data.journals %}
1. [{{ pub.name }}]({{ pub.url }})\
   *{{ pub.authors }}*\
   *{{ pub.conf }}*
{% endfor %}

## Workshops

{% for pub in site.data.workshops %}
1. [{{ pub.name }}]({{ pub.url }})\
   *{{ pub.authors }}*\
   *{{ pub.conf }}*
{% endfor %}

## Theses

{% for pub in site.data.theses %}
1. [{{ pub.name }}]({{ pub.url }})\
   *{{ pub.authors }}*\
   *{{ pub.conf }}*
{% endfor %}
