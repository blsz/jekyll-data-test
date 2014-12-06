---
title: jekyll-data-test
layout: default
---

This is created using [jekyll datafiles](http://jekyllrb.com/docs/datafiles/):

{{site.data.foo}}

The data is also available directly [for download]({{site.baseurl}}/api/foo.yml).

---

How neat is this?

{% for justice in site.data.justices.justices %}

	{{justice}}

{% endfor %}

[Download]({{site.baseurl}}/api/justices.json)