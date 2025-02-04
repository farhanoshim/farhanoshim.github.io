---
layout: page
title: "Publications"
permalink: /publications/
---

{% for pub in site.publications %}
1. *{{ pub.title }}*, {{ pub.author }}, *{{ pub.conference | default: pub.journal }}*, {{ pub.year }}.  
**Abstract:** {{ pub.content | markdownify }}  
[Link]({{ pub.url }}) | [PDF]({{ pub.pdf }}) | [Video]({{ pub.video }})
{% endfor %}
