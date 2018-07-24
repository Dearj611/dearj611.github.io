---
layout: default
---

<body>
  <div class="web-bg">
  <div class="index-wrapper">
    <div class="aside">
      <div class="info-card">
        <h1>Sica </h1>
        <h2>♡ My Secret Garden ♡</h2>
        <a href="http://weibo.com/sicajessica" target="_blank"><img src="http://www.weibo.com/favicon.ico" alt="" width="25"/></a>
      </div>
    </div>

    <div class="index-content">
      <ul class="artical-list">
        {% for post in site.categories.blog %}
        <li>
          <a href="{{ post.url }}" class="title">{{ post.title }}</a>
          <div class="title-desc">{{ post.description }}</div>
        </li>
        {% endfor %}
      </ul>
    </div>
  </div>
  </div>
</body>
