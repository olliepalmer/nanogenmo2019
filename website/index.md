---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: Directory Directory
---


# Directory Directory
{: .no-toc}

<strong>Home of the directory. Look for the directory for all your directory needs!</strong>

Created for NaNoGenMo 2019 by [Ollie Palmer](https://olliepalmer.com).

----


{% for post in site.pages %}<a href="{{ post.url }}">{{ post.title }}</a> {% endfor %}
