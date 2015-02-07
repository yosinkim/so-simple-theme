---
layout: post
title: "서브라임 마크다운 사용법"
excerpt: "서브라임 마크다운 플러그인으로 깃허브 블로그에 글 쓰는 방법에 대한 요약"
category: blog
tags: [hello, post]
comments: true
---

## 서브라임

[서브라임 텍스트 3](http://www.sublimetext.com/3)를 설치한다.

1. [패키지 매니저 설치](https://packagecontrol.io/installation#st3)를 설치한다.
2. MarkdownEditing, OmniMarkupPreviewer, OpenURL, Table Editor을 설치한다.


### 서브라임이 좋은 점

1. 패키지가 많다.
2. 자동 저장이 된다.

### github 블로그 로컬에 설치

1. [ 블로그 저장소](https://github.com/yosinkim/yosinkim.github.io) 에서 로컬로 클론(복사)한다. 터미널에서 Documents 디렉토리로 이동한 다음:

    git clone https://github.com/yosinkim/yosinkim.github.io.git 

2. yosinkim.github.io 디렉토리의 _posts 에 있는 마크다운 파일을 편집하거나 추가한다.
3. 블로그 디렉토리에서 다음 명령어를 입력하여 깃허브의 저장소를 업데이트한다.
    
     git add . -A
     git commit -m "Add That Post"
     git push origin master

업데이트가 최대 10분 정도 걸리 경우도 있다.

### 이미지

블로그의  특정 디렉토리에 이미지를 올리거나 이미지 공유 서비스의 공유링크를 이용한다.

![펭돌이와 펭순이의 뽀뽀: 디렉토리](/images/bio-photo.jpg)
![펭돌이와 펭순이의 뽀뽀: 드랍박스](https://www.dropbox.com/s/w6bu1c8h0c8ud1u/bio-photo.jpg?dl=0)