layout: archive
classes: container-fluid
title: "Publications"
permalink: /publications/
author_profile: true



You can also find my articles on my 
<u>
  <a href="https://scholar.google.com/citations?user=JjF9FRwAAAAJ&hl=en" 
     target="_blank" 
     rel="noopener noreferrer">
     Google Scholar
   </a>
</u> 
profile.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
