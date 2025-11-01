---
layout: home
title: Homepage
---

Hello, and thanks for stopping by.

This is my current collection of a working poetry epic that has been on my mind for awhile.
For several years I have been knee deep in software development.  A rewarding, but, mind-numbing endeavor has had my insides screaming to balance my mind out with some other output for creativity.

While driving back from picking up coffee one Saturday morning, the idea for this epic stormed my mind.  I could not part with the internal tug to bring it to life.  So I set out to write my version of a postmodern version of America.  One of dystopia, but underneath that, one still of supreme hope for humankind.

I really do not know how long this will go, I have dozens of topics to cover, and an entire American continental topography to navigate.

More than anything, I appreciate you stopping by to read my prose and I hope it resonates with you.  And maybe it'll give you the inspiration to make a change in your life that you have been hesitant to do.

Feedback is welcome, contact me here with your thoughts:

Email: npacchioli@gmail.com
X: SupplyQNick

Happy Reading!

## Chapters

{% for post in site.categories.chapters reversed %}
- **{{ post.title }}**
  [Read Chapter →]({{ post.url }})
{% endfor %}

{% if site.categories.chapters.size == 0 %}
*No chapters found.*
{% endif %}
