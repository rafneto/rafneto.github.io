---
layout: default
author: "Rui Neto"
---

<table class="tg"><thead>
  {% for post in site.posts %}
    <tr>
      <td class="tg-73oq">
        <img src="assets/images/{{post.thumbnail}}" alt="{{post.tags}}" width="50" height="50">
      </td>
      <td class="tg-73oq">
        <a href="{{ post.url }}">
          <h2>{{ post.title }}</h2>
        </a>
        <span>{{post.tags}} {{post.date}}</span>
        </td>
    </tr>
      
  {% endfor %}
</thead>
</table>
