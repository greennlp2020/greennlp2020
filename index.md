---
title: Home
---

# GreenNLP

{% include figure.html img="nature_green.jpg" alt="intro image here" caption="" width="75%" %}

<div class="toc" markdown="1">
## Contents:

{% for lesson in site.pages %}
{% if lesson.nav == true %}- [{{ lesson.title }}]({{ lesson.url | absolute_url }}){% endif %}
{% endfor %}
</div>

