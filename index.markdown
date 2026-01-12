---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Dan Sagher
---
![Name]({{ site.baseurl }}/assets/images/name.png)

## About
Born and raised in Ann Arbor, Michigan. Former professional guitarist. Currently building MindMosaic and studying data science at Michigan State University.

## MindMosaic

- [MindMosaic](https://www.mind-mosaic.co/)

## Essays

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}

## Contact

- **Email:** dsagher@mind-mosaic.co
- [LinkedIn](www.linkedin.com/in/dan-sagher/)
- [Instagram](https://www.instagram.com/dansagher/)

I read everything. Replies may be slow.




