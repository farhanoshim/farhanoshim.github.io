<!-- ---
layout: single
title: "Publications"
permalink: /publications/
author_profile: true
--- -->
---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
classes: full-width
---

You can also find my articles on 
<u>
  <a href="https://scholar.google.com/citations?user=JjF9FRwAAAAJ&hl=en" 
     target="_blank" 
     rel="noopener noreferrer">
     my Google Scholar profile
  </a>
</u>.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
