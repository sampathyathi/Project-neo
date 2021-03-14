---
author: Sam
layout: demo
---

# Home Page

My name is {{ page.author }}.

The {{ site.What }} is {{ site.When }}.

{% for item in file2 %}
  {{ item.name }}, {{ item.place }}
{% endfor %}
