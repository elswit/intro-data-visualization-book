---
slug: book
title: Demo Book
abstract: A draft for an introductory data visualization book set in Jekyll Chapterbook theme.
---

By Authors

Copyright &copy; {{"now" | date: "%Y"}} by {{site.author}} and other Authors.

Last updated: {{ "now" | date: "%B %e, %Y" }}

{% if site.baseurl_canonical %}
  The latest version of this book can always be found at  
  <a href="{{site.baseurl_canonical}}{{page.url}}">{{site.baseurl_canonical}}{{page.url}}</a>.
{% endif %}

---
```
This file is located at: {{ page.path }}
```
---
