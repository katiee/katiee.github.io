---
layout: page
---
{% include JB/setup %}

{% for post in site.posts %}
* {{ post.date | date_to_string }}  <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a><br/>
  {{ post.content }}
{% endfor %}

## 学习
* Git
* GitHub
* Markdown
* Pandoc
* Kindle

---

## 读书 

