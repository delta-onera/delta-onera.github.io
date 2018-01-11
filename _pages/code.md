---
layout: archive
title: "Code"
permalink: /code/
author_profile: true
---

{% include base_path %}

# Github
[https://github.com/delta-onera](https://github.com/delta-onera)

---
# Code available with description

{% for post in site.code reversed %}
  {% include archive-single.html %}
{% endfor %}

---
# Code linked to papers

Here is a list of the publications associated with code.
For a complete list of publication associated with the project, check the publication tab.

{% for post in site.publications reversed %}
    {% if post.code %}
        {% include archive-single-pub.html %}
    {% endif %}
{% endfor %}

