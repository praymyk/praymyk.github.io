---
layout: post
title:  "깃 블로그 생성방법"
date:   2023-04-26 19:38:57 +0900
categories: jekyll update
---
깃 블로그는 블로그 설정 파일을 깃 홈페이지 내 repositories 공간에 업로드하여 관리하는 것으로 이해
로컬 PC에 리포지토리에 존재하는 블로그 구성 원본을 복제(Clone) 하여 수정한뒤 업로드(Push)를 반복하는 것으로 관리함
리포지토리에 블로그를 생성한 상태에서 간략한 관리 순서는 아래와 같음

1. 터미널(Git bash)을 로컬 PC내 원하는 공간에서 실행하여 깃 리포지토리 블로그 파일을 복제한다
{% highlight ruby %}
git clone https://github.com/praymyk/praymyk.github.io.git
git clone (본인의 리포지토리 주소)
{% endhighlight %}

2. clone된 블로그 파일을 수정 했다면 리포지토리아 push하여 반영한다  / post 글 수정시 "2."를 "1."로 인식하는 문제가 있어 나중에 확인해야함
   push는 업로드 + 커밋 과정이 함께다? 줄바꾸기도 확인 필요.....
{% highlight ruby %}
git commit -m "할말"
git push origin main
{% endhighlight %}
정확한 이유는 확인하지 못했지만 commit후 push를 해야 리포지토리에 정상 반영된다.

3. 지킬 한글 튜토리얼 주소
{% highlight ruby %}
http://jekyllrb-ko.github.io/
{% endhighlight %}
 

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
