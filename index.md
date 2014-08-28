---
layout: page
title: SCSB Clicks
tagline: An index of self-criticisms!
---
{% include JB/setup %}

###Shutterbugs turn Nomads

The Self-critic Shutterbug is migrating - again! A few years back, we moved from wordpress.com to self-hosted wordpress.
That was also the time SCSB got its own domain name. This time, we are moving away from wordpress to a static site.
We came to the conclusion that the hosting charges simply aren't worth for a site that is only updated a handful of times a year.

This site is now using [jekyll](http://jekyllrb.com/) and hosted on [Github Pages](http://pages.github.com/).
What's better, this is now an [open source](https://github.com/selfcriticshutterbug/selfcriticshutterbug.github.io) site!


###While We're on the Road ...

While the migration is being performed, you might notice a few glitches in the site. For example, photos might not be centered correctly, the borders might have disappeared, and so on. But fear not - when we are done, we hope normalcy will be restored.

We're also looking into infusing a breath of fresh air by incoporating a photo-blog appropriate minimal theme. That might take time though.

The new site is set up to use disqus for comments. We are working hard to ensure that your comments are retained.

Stay tuned for more updates. And do keep visiting!



###Archive

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

