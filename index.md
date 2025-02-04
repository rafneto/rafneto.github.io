---
layout: default
author: "Rui Neto"
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">
      <h2>{{ post.title }}</h2>
      <table class="tg"><thead>
        <tr>
          <td class="tg-73oq">
            <img src=images/{{post.thumbnail}}/>
          </td>
          <td class="tg-73oq">
            <span>{{post.tags}} {{post.date}}</span>
            <p>{{post.short_description}}</p></td>
        </tr></thead>
      </table>
      </a>
    </li>
  {% endfor %}
</ul>
