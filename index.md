---
layout: default
---
![PC](./assets/images/ibm_ps2_30_small.jpg)

[About](./about)

For various projects.

# Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{post.date}} - {{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
