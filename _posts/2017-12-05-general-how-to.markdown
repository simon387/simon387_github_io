---
layout: post
title:  "General Jekyll how to"
date:   2017-12-05 11:51:33 +0100
categories: jekyll update
---
# how to create a new post

1. create a new file ```vim ./_posts/yyyy-mm-dd-title.markdown```
1. done!

# how to create a new page

1. create a new file ```vim ./new_page.markdown```
1. example of content:

{% highlight jekyll %}
  ---
  layout: page
  title: Other page
  permalink: /other/
  ---

  test new page
{% endhighlight %}
