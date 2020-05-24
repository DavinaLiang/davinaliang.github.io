---
layout: archive
title: "Presentation"
permalink: /presentation/
author_profile: true
---
[**National Chain Retailer Attraction Plan (City of Rochester)**](/files/Pitch.pdf)
<br />
![](/images/cr.png)

[**Crimes in Boston**](/files/pre4.pptx)
<br />
![](/images/1.png)

[**Southwest Conquistador Beer**](/files/a1.pdf)
<br />
![](/images/2.png)

[**Yogurt Flavors**](/files/a2.pdf)
<br />
![](/images/3.png)

[**Toy Horse Conjoint Experiment**](/files/a3.pdf)
<br />
![](/images/4.png)

[**Wine Retailer**](/files/a4.pdf)
<br />
![](/images/5.png)


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
