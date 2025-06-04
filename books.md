---
layout: home
title: Books
permalink: /Books/
---

Please see [my publications page]({{site.baseurl}}/publications) for a full list including articles and presentations, or [view my page on ResearchGate](https://www.researchgate.net/profile/Jonathan_Firth2/projects).

{% for book in site.data.books %}

## {{book.title}}

![{{book.title}} cover]({{site.baseurl}}/assets/{{book.cover}}){: width="50%" }

{{book.description}}

[Find out more and buy here.]({{book.link}})
<br><br><br>
{% endfor %}