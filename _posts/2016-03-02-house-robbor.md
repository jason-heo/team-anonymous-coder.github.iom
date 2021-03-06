---
layout: post
title: "House Robbor"
author: anonymous01
tag: "dynamic programming"
---

- 출처: [https://leetcode.com/problems/house-robber/](https://leetcode.com/problems/house-robber/)

문제
--

당신은 도둑이다. 길가에 n개의 연속된 집이 있는데, 집 마다 경보기가 연결되어 있다. 만약 연속된 2개의 집이 털리는 경우 경찰에게 바로 연락이 가도록 되어 있다. n개의 집에는 0 이상의 돈이 저장되어 있다. (대출을 훔칠 도둑은 없겠지?)

경찰에게 신고되지 않고 털 수 있는 최대 금액은 얼마인가?

문제 설명
-----

h*n*은 집 번호이고, 아래의 괄호는 집에 저장된 돈의 액수이다.

### 예1)

{% highlight %}
h0 <---> h1 <---> h2
(10)     (20)      (5)
{% endhighlight %}

이 경우, h1 집을 털 때 최대 금액을 훔칠 수 있다.

### 예2)

아래의 경우에는 (h0+h2)를 털어야 최대 금액을 털 수 있다.

{% highlight %}
h0 <---> h1 <---> h2
(10)     (20)     (20)
{% endhighlight %}

### 예3)

여기부터가 좀 까리하다

{% highlight %}
h0 <---> h1 <---> h2 <---> h3
(20)     (10)     (25)     (30)
{% endhighlight %}

집을 털 수 있는 경우 수가 많아졌는데, 0 이상의 돈이 숨겨있으므로 1개 터는 것을 생략한다면,

- h0 + h2 = 45
- h0 + h3 = 50
- h1 + h3 = 40

위와 같은 3가지 경우가 있고, (h0+h3)를 터는 것이 최대가 된다.

공식 유도
-------

- TBD

풀이
--

- TBD
