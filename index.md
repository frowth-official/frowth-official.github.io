---
title: Frowth
feature_text: >
  ## 주식회사 프로스

  주식회사 프로스 github.io 공식 홈페이지 입니다.
feature_image: "https://frowth-official.github.io/assets/default-offline-image.png";
excerpt: >-
  주식회사 프로스 github.io 공식 홈페이지 입니다.
---

주식회사 프로스 github 공식 홈페이지 입니다.

## 프로스 운영 사이트

- <a href="https://newsdao.kr" rel="dofollow">newsdao.kr</a>
- <a href="https://partnersix.com" rel="dofollow">partnersix.com</a>
- [X(Twitter)](https://x.com/frowth_official)
- [Velog](https://velog.io/@frowth_official/posts)
- [Threads](https://www.threads.net/@frowth_official)
- [Medium](https://frowth.medium.com/)

<ul class="post-list">
  {% for post in site.posts limit:3 %}
    <li class="post-item">
      <a href="{{ post.url }}">
        <div class="post-box">
          <div class="thumbnail" style="background-image: url('{{ post.feature_image }}');"></div>
          <div class="post-content">
            <h3>{{ post.title }}</h3>
            <p>{{ post.feature_text }}</p>
          </div>
        </div>
      </a>
    </li>
  {% endfor %}
</ul>