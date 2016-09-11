---
layout:	default
title:	hello, Haho
---
<h2>{{ page.title }}</h2>
<p>Hello Haho</p>
<p>Hahooooooooooooooooooooooo</p>
<p> {{ page.date | date_to_string }} </p>
<h2>author: {{ site.author }}</h2>
<hr>
url:<a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a>
<hr>
url:<a href="{{ site.url }}{{ post }}">{{ post }}</a>
<hr>
email: {{ site.email }}
<br>
<p>haha123123123</p>
