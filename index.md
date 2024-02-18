layout: post

# TODAY I LEARNED SOMETHING

This is the homepage of my this blog guys. In this blog i will be sharing my thoughts and some projects on programming and other topics while studying and trying to revision things I end up forgetting.

## Latest Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
