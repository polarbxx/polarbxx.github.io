---
layout: single
title: "블로그를 시작합니다"
date:   2026-04-14 23:30:32 +0900
categories: [blog, start]
permalink: /start/
---
Jekyll와 GitHub Pages로 블로그를 시작했습니다.

앞으로는 개발 기록, 배운 점, 트러블슈팅 내용을 이곳에 차근차근 쌓아갈 예정입니다.

첫 글을 작성하는 방법은 간단합니다.

`_posts/YYYY-MM-DD-title.md` 형식으로 파일을 만들고, 파일 상단에 front matter를 적어주면 됩니다.

예를 들어:

{% highlight markdown %}
---
layout: post
title: "새 글 제목"
date: 2026-04-14 23:40:00 +0900
categories: [dev]
---
본문을 여기에 작성합니다.
{% endhighlight %}

로컬에서 확인할 때는 아래 명령어를 사용하면 됩니다.

{% highlight bash %}
bundle exec jekyll serve
{% endhighlight %}
