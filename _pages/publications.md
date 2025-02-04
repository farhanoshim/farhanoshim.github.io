---
layout: page
title: "Publications"
permalink: /publications/
---

{% for pub in site.publications %}
1. *{{ pub.title }}*, {{ pub.author }}, *{{ pub.journal }}*, {{ pub.year }}. [Link]({{ pub.url }})

{% endfor %}
