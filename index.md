---
layout: default
---

# Welcome to My Beautiful Jekyll Website

This is the homepage of my website. You can customize this page with your own content.

## About Me

Hello, I'm [Your Name]. I'm a [Your Profession] based in [Your Location].

## Blog Posts

Check out some of my latest blog posts:

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) ({{ post.date | date: "%B %d, %Y" }})
{% endfor %}

## Contact Me

You can reach me at [your.email@example.com](mailto:your.email@example.com) or connect with me on [Twitter](https://twitter.com/yourtwitterhandle).
