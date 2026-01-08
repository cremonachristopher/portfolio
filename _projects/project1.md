---
layout: project
title: Portfolio professionnel
technologies: [Jekyll, Markdown, GitHub Pages]
---

{% for project in site.projects %}
### {{ project.title }}

{{ project.excerpt }}

**Technologies :** {{ project.technologies | join: ", " }}


[site Klivio](https://cremonachristopher.github.io/projet_kliblio/)
---
{% endfor %}