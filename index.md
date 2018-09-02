---
layout: article
permalink: /
share: false
logo: logo.png
---

Welcome to the homepage of **UK Quizbowl** --- the organisation for all things to do with student buzzer quizzing in the UK.

Quizbowl is, essentially, a competitive version of the *University Challenge* TV show, but with some differences in focus ---  if you are new to this, why not check out our [introduction to quizbowl]({{ site.url }}{{ site.baseurl }}/intro/)? You can also find the details of upcoming quizbowl tournaments on the [events page]({{ site.url }}{{ site.baseurl }}/events/), with some common questions answered in the [FAQ section]({{ site.url }}{{ site.baseurl }}/events-faq/).


### Latest blog posts

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
