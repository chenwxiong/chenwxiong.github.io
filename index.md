## 欢迎

我是陈伟雄，一名产品经理。这是我分享个人作品和工作心得的个人网站。

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
