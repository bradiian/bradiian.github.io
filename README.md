---
layout: default
---

# bradiian.github.io

안녕하세요 브래디 입니다.

생각글을 공유합니다.

재미있게 읽어주시면 좋겠습니다.

2023-01-03. 화

theme by . https://github.com/pages-themes/minimal

{% for post in site.posts %}

  <article>
    <h2>
      <a href="{{ post.url }}">
        {{ post.title }}
      </a>
    </h2>
    <time datetime="{{ post.date | date: "%Y/%m/%d" }}">{{ post.date | date: "%Y/%m/%d" }}</time>
    {{ post.content }}
  </article>
{% endfor %}
