---
tags: nav
eleventyNavigation:
  key: Wiki
  order: 4
  permalink: false
---

{% raw %}
{% if locale == 'en' %}
  <meta http-equiv="refresh" content="0; url=/en/wiki/">
{% elseif locale == 'it' %}
  <meta http-equiv="refresh" content="0; url=/it/wiki/">
{% else %}
  <!-- Default fallback redirect if locale is not specified -->
  <meta http-equiv="refresh" content="0; url=/en/wiki/">
{% endif %}
{% endraw %}
