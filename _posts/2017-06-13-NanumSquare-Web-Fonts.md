---
layout: post
title: 나눔스퀘어 웹폰트 공유(rawgit)
tag: NanumSquare, Fonts
---

나눔 스퀘어 웹폰트 Light 글씨체를 써야 할 일이 종종 있어 구글링으로 찾는 것보다 만드는 게 빠를 것 같아 Github에 웹폰트를 올리고 rawgit을 이용해 사용하고 있다.

# NanumSquare

> 반듯한 직선으로 제목에 잘 어울리며 모바일에서도 잘 보이는 글꼴입니다. 꼭 필요한 2,350자만을 추려 용량을 가볍게 줄였고 웹 환경에서 보다 편리하게 사용 가능합니다. <http://hangeul.naver.com/2016/nanum>

## 옵션

Regular(400), Bold(700), Extra Bold(800), Light(300) 지원됩니다.

## 사용방법

### link 방식 (권장)

``` html
<link rel="stylesheet" type="text/css" href="https://cdn.rawgit.com/moonspam/NanumSquare/master/nanumsquare.css">
```

### import 방식

``` css
@import url(https://cdn.rawgit.com/moonspam/NanumSquare/master/nanumsquare.css);
```

## 적용

### CSS (예)

```css
body        { font-family: 'NanumSquare', sans-serif; }
.normal     { font-weight: 400 }
.bold       { font-weight: 700 }
.bolder     { font-weight: 800 }
.light      { font-weight: 300 }
```

출처: <https://github.com/moonspam/NanumSquare>