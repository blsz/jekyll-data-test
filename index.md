---
title: jekyll-data-test
layout: default
---

This is created using [jekyll datafiles](http://jekyllrb.com/docs/datafiles/):

{{site.data.foo}}

The data is also available directly [for download]({{site.baseurl}}/data/foo.yml).

---

How neat is this that I can both consume the datafile as data...

{% for justice in site.data.justices.justices %}
	{{justice}}
{% endfor %}

... and at the same time make it available for [download]({{site.baseurl}}/data/justices.json)?

---

You can read more about how this works at <https://esq.io/blog/posts/dogfooding-with-jekyll>.

