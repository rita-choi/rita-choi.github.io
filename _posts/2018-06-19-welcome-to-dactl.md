---
title: Jekyll*dactl 템플릿을 활용한 기술 블로그
layout: post
tags:
- dactl
- jekyll
hero: https://source.unsplash.com/collection/430471/
overlay: red
published: true
---

`_posts` 경로에서 블로그 포스팅 확인 가능합니다. 포스트 or 변경사항이 있다면 적용 후  `jekyll serve` 로 서버를 재시작해 줍시다. :point_up:
{: .lead}
<!–-break-–>
서버를 재시작해 주면 자동으로 변경사항이 적용됩니다.

jekyll의 admin plugin을 사용하지 않는다면 포스팅할 파일을  `_posts`  경로에 `YYYY-MM-DD-name-of-post.ext` 적용합니다. (프론트에 반영할 사항도 포함해서).


지킬은 다들 아시겠지만 code snippets 기능에도 강합니다:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Jekyll에 대해 더 알고 싶으시면  [Jekyll docs][jekyll] 관련 문서 링크로,  각종 버그/에러 보고는 깃허브로  [Jekyll’s GitHub repo][jekyll-gh] 
문의사항은  [Jekyll’s dedicated Help repository][jekyll-help] 로 부담없이 접속 부탁 드립니다.

[jekyll]:      http://jekyllrb.com
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-help]: https://github.com/jekyll/jekyll-help

:exclamation: 참고용으로 간략히 번역하였습니다.