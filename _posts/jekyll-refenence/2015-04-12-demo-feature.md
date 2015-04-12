---
layout: test
title:  "Feature"
categories: jekyll-demo
---

### 코드 강조

{% highlight javascript linenos %}

var fn = function() {

    return "string" + 1;
}

{% endhighlight %}


### 이미지 / 자원 삽입

![친절한 스크린샷](/assets/test.jpeg)

### 다른 포스트 링크

[Post Link]({% post_url 2015-03-04-code-highlight %})

### 포스트 목록 표시

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{post.excerpt | remove: '<p>' | remove: '</p>'}}
    </li>
  {% endfor %}
</ul>