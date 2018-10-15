---
layout: post
title: 나눔바른고딕 경량화 웹폰트 공유
tag: [NanumBarunGothic, Fonts]
---

요즘 나눔바른고딕을 사용하는 일이 많아져서 웹폰트가 있는지 찾아보니 구글 폰트에서 바른고딕은 없었고 github이나 무료 CDN에 종종 찾을 수 있었지만, 모바일 웹에서 사용하기엔 크나큰 용량이어서 직접 만들어 보았습니다.  
실사용되는 한글 및 특수문자 **3,705자**만 추려 용량을 약 **65% 축소**하였습니다.

## NanumBarunGothic

> 모바일에 최적화된 정통 고딕 글꼴입니다. 글꼴이 가장 깨끗해 보이는 두께와 자간을 연구해 또렷하게 보이도록 만들었습니다. 돌출 형태나 곡선이 없어 작은 화면에서도 잘 읽힙니다.  
`https://hangeul.naver.com/2017/nanum`

### 옵션

Regular(400), Bold(700), Light(300), Ultra Light(200) 지원됩니다.

### 사용방법

#### link 방식 (권장)

```html
<link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/gh/moonspam/NanumBarunGothic@1.0/nanumbarungothicsubset.css">
```

#### import 방식

```css
@import url("https://cdn.jsdelivr.net/gh/moonspam/NanumBarunGothic@1.0/nanumbarungothicsubset.css");
```

#### 적용

##### css 예시

```css
body  { font-family: 'NanumBarunGothic', sans-serif; }
```

### 참고 사이트

- [스포카 한 산스와 글꼴 경량화](https://spoqa.github.io/2015/10/14/making-spoqa-han-sans.html)
- [웹폰트 경량화: 폰트툴즈의 pyftsubset을 사용한 폰트 서브셋 만들기](https://www.44bits.io/ko/post/optimization_webfont_with_pyftsubnet)
