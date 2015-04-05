---

layout:     default
title:      Cream of the Craft Originals
type:       page
navigation: true

date:       2015-04-05
image:      header-bear.jpg
excerpt:    "It’s not like we have seen a design on the internet and made a prototype of it the next day. <br/> It’s all about.. each design has a <strong>STORY</strong>…"

gradient:   1

---
{% include fb-sdk.html %}

<div class="summary">

  <p>We'd like to inspire you with some stories. These are a compilation of all our original designs and its story behind them. Through these amazing flowers, we created something unique and something new. To know more about the unique works we've done, check this out. <a href="/made-with-love.html" title="Continue" class="more">Continue</a></p>

</div>


<h2>Our Story</h2>
<p>Because every design has a story.</p>

{% for post in site.categories.originals %}

  {% include summary.html %}
  
{% endfor %}