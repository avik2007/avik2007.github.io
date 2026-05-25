---
layout: single
title: "Publications"
permalink: /publications/
author_profile: true
---

{% for pub in site.data.publications %}
### {{ pub.title }}
{{ pub.authors }} — *{{ pub.venue }}*, {{ pub.year }}

{% if pub.links.pdf %} [[PDF]({{ pub.links.pdf }})] {% endif %}
{% if pub.links.code %} [[Code]({{ pub.links.code }})] {% endif %}

---
{% endfor %}
