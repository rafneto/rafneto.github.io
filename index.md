---
layout: default
author: "Rui Neto"
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">
      ## {{ post.title }}
      _{{post.tags}} {{post.date}}_
      {{post.short_description}}
      ![Ŵelcome](images/{{post.thumbnail}})
      </a>
    </li>
  {% endfor %}
</ul>