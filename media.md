---
layout: default
---
<section id="articles">
  <h2>メディア掲載</h2>
  <ul>
    {% for article in site.data.articles %}
    <li><span>{{article.date}}</span><a href="{{article.url}}">{{article.title}}</a></li>
    {% endfor %}
  </ul>
</section>
