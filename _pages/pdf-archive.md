---
title: PDF Archive Index
author_profile: false
permalink: /pdf-archive/
suggestedcitiation: false
---
## PDF Archive

<!-- more -->

{% assign pdf_files = site.static_files | where: "pdf", true %}
{% for mypdf in pdf_files %}
  [⤓ {{mypdf.name}}]({{ mypdf.path }})
{% endfor %}
