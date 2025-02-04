# Personal Blog

## articles

{% for post in site.posts %}
* [{{ post.date | date: "%Y-%m-%d" }} {{ post.title }}](/joost{{ post.url }})
{% endfor %}
