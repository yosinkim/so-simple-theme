---
layout: post
title: "지킬 테마 적용"
excerpt: "지킬 테마를 바꾼 후에 수정하는 방법"
category: blog
tags: [jekyll]
comments: true
---





## 지킬 테마 적용

1.하고 싶은 테마를 고른다. (ex.내가사용한 테마[So Simple](http://jekyllthemes.org/themes/so-simple/))
2.홈페이지를 클릭 후 포크 후에 클론하기.

	git clone https://github.com/yosinkim/so-simple-theme.git yosinkim.github.io

터미널에서 로컬에 클론한다.

### 로컬 so-simple-theme에서 

	jekyll s -w 

	sudo gem install jekyll-sitemap   

### 주요 변경 사항

_config.yml 에서 변경하기

- title(블로그제목) 
- description(블로그소개)
- Site owner에서 name, email, disqus-shortname

disqus-shortname은 [Disqus](https://disqus.com/) 에서 admin에 들어가 setting을 보면 shortname이 있다.

글씨체를 바꾸기 위해서 _sass에서 _variabless.scss로 들어가 $alt-font 'volkhov'를 한글 지원을 하기위해 "나눔고딕", NanumGothic 으로 변경해준다.

/_data/navigation.yml title들을 한글로 변경.

### 포스팅

_posts에서 blog에 내 게시글을 옮긴다. 여기서는 description 이 excerpt 로 사용된다. 또한 코멘트를 추가하기 위해서는 comments: true 를 넣어줘야한다.

### GitHub

     git add . -A
     git commit -m "Add That Post"
     git push origin master

위의 명령어로 로컬의 변경사항을 적용한다.

저장소 이름을 yosinkim.github.io 로 변경한다.



