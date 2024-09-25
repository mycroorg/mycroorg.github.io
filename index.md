---
---

{% translate_file index.md %}

{% if site.lang == "en" %}
  {% capture link1 %}{{ site.baseurl_root }}/es{{ page.url}}{% endcapture %}
  <a href="{{ link1 }}" >Español</a>
{% elsif site.lang == "es" %}
  {% capture link2 %}{{ site.baseurl_root }}/en{{ page.url}}{% endcapture %}
  <a href="{{ link2 }}" >English</a>
{% endif %}