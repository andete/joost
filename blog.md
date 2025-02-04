# Personal Blog

## articles

{% for post in site.posts %}
* [{{ post.title }}]({{ "joost/" post.url }})
{% endfor %}
