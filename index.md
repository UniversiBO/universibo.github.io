---
layout: page
title: UniversiBO
tagline: fatto dagli studenti, per gli studenti
---
{% include JB/setup %}
Benvenuti nel nuovo sito web della documentazione tecnica [UniversiBO](https://www.universibo.unibo.it/)

## Ultime notizie
{% for post in site.posts limit: 5 %}
### {{ post.date | date:"%d/%m/%Y" }} [{{ post.title }}]({{ post.url}})
{{ post.content | strip_html | truncatewords: 50 }}
{% endfor %}

## Documentazione 
* [Wiki associazione](https://wiki.universibo.unibo.it/)
* [Wiki progetto (EN)](https://github.com/UniversiBO/UniversiBO/wiki)

### Vecchio materiale
* [Documentazione in italiano](/v2/)


