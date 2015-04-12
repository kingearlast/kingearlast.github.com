---
layout: post
title:  "Style"
categories: jekyll-demo
---

## 그것이 알고 싶다 – Spinbox로 React 겉 핥기 

센스있는 개발자라면 기술 관련 위클리 메일을 하나정도는 받아보고 있을 것이다. 나 역시 많은 위클리 메일을 구독하고 있다. 무슨 위클리가 그리 많은지… 이젠 부담스러워서 몇 개 구독을 끊을까 생각중. 아무튼 매주 쏟아지는 정보 중 10%도 못 읽고 넘기고 있지만 JavaScript 위클리는 꼬박꼬박 챙겨보려고 애쓰고 있다. 뭔가 JavaScript로 밥 벌어 먹고 사는 사람의 의무 같다고나 할까? 그래서 주말 아침 잠자리에서 눈 뜨면 습관적으로 JavaScript 위클리를 훑어본다.

## React, 넌 또 뭐니?

React를 한 문장으로 정의를 하자면,
‘페이스북이  웹 UI를 개발할 때 사용하려고 만든 자바스크립트 라이브러리라’고 할 수 있다.

![친절한 스크린샷](/assets/demo.png)

### React의 특징

* JSX(JavaScript XML)
* 가상 DOM(Virtual DOM)
* 단방향 데이터 플로우(Unidirectional Data Flow)

#### 예제 코드 demo.css

{% highlight css linenos %}

<link rel="stylesheet" type="text/css" href="yozm_common.css" /> <!-- reset, common요소 -->
<link rel="stylesheet" type="text/css" href="yozm_top.css" /> <!-- 콘텐츠관련 -->

.tit { font-size:14px; line-height:18px } 
.news li { float:left; margin:0 10px 0 0 }

{% endhighlight %}

    react-0.12.0.js와 JSXTransformer-0.12.0.js 파일을 불러오는데, 
    두 파일이 하는 역할은 뒤에서 설명한다.