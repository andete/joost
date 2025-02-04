# Personal Blog

## articles

{% for post in site.posts %}
* [{{ post.title }}]({{ post.url }})
{% endfor %}
