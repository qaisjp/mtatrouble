---
---

<h2>posts</h2>

<ul>

{% for page in site.pages %}
<li>
  <a href="{{ page.url }}">{{ page.title }}</a>
</li>
{% endfor %}
</ul>
