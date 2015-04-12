---
layout: post
title:  "[Drafts] Syntax Reference"
---

### 코드 강조

{% highlight javascript linenos %}

var fn = function() {

    return "string" + 1;
}

{% endhighlight %}


### 이미지 / 자원 삽입

![친절한 스크린샷](/assets/test.jpeg)

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>