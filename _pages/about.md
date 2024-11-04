---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm a research scientist in the [VITA lab @ EPFL](https://www.epfl.ch/labs/vita/), passionate about developing applied AI solutions. 
I did my PhD under the supervision of [Alexandre Alahi](https://people.epfl.ch/alexandre.alahi?lang=en) and recieved my master's and bachelor's degrees in Electrical engineering from [Sharif university of technology](https://en.sharif.edu/). 

My PhD thesis, conducted in collaboration with [Honda](https://www.honda.com/), investigates the generalization of autonomous robotic systems. During my PhD, I completed a six-month research internship at [Five AI](https://www.five.ai/) (now acquired by Bosch), a leading company in self-driving technology in the UK.

I am looking for great teams to join. Feel free to drop me a massage if you know one :)

# News

{% include base_path %}
{% capture written_year %}'None'{% endcapture %}
{% for post in site.posts  limit:5  %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  {% include archive-single.html %}
{% endfor %}

### [See more...]({{ site.url }}/updates)
