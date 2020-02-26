---
layout: archive
title: "Presentation"
permalink: /presentation/
author_profile: true
---
**Crimes in Boston**
<br />
![](/images/1.png)

**Southwest Conquistador Beer**
<br />
![](/images/2.png)

**Yogurt Flavors**
<br />
![](/images/3.png)

**Toy Horse Conjoint Experiment**
<br />
![](/images/4.png)

**Wine Retailer**
<br />
![](/images/5.png)


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
