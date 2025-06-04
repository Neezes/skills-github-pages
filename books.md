---
layout: page
title: Books
permalink: /Books/
---

Please see [my publications page](/publications) for a full list including articles and presentations, or [view my page on ResearchGate](https://www.researchgate.net/profile/Jonathan_Firth2/projects).

{% for book in site.data.books %}

# {{book.title}}

![{{book.title}} cover](/assets/{{book.cover}})

{{book.description}}

[Find out more and buy here.]({{book.link}})

{% endfor %}