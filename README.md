# 제목(Header) <!--#갯수에 따라 h1~h6로 나뉘어짐-->

# 제목 1

## 제목 2

### 제목 3

# 문장(Pragraph)

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세

# 줄바꿈(Line Breaks)

<!--띄어쓰기 두번 넣어주면 줄바꿈된다. 또는 <br/>-->

동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세  
동해물과 백두산이 마르고 닳도록<br/>
하느님이 보우하사 우리나라 만세

# 강조(Empasis)

_이텔릭_  
**두껍게**  
_**이텔릭 + 두껍게**_  
~~취소선~~  
<u>밑줄</u>

# 목록(List)

1. 순서가 필요한 목록
1. 순서가 필요한 목록
   1. 순서가 필요한 목록
   1. 순서가 필요한 목록
1. 순서가 필요한 목록

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
  - 순서가 필요하지 않은 목록
  - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록

# 링크(Links)

[GOOGLE](https://google.com)  
[GOOGLE](https://google.com "GOOGLE로 이동!")  
<a href="https://google.com" title="GOOGLE 이동!" target="_blank">GOOGLE</a>

<!-- target은 마크다운용이 없음. target을 쓸려면 html문법 사용 -->

# 이미지(Image)

<!-- 이미지만 -->

![HEROPY](https://heropy.blog/css/images/logo.png)

<!-- 이미지에 링크달기 -->

[![HEROPY](https://heropy.blog/css/images/logo.png)](https://heropy.blog/2019/04/24/html-css-starter/)

# 인용문(BlockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
> (네이버 국어 사전)

> 중첩된 인용문
>
> > 중중첩된 인용문

# 인라인(inline) 코드 강조

CSS에서 `background` 혹은 `background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.

# 블록(block) 코드 강조 코드 자체를 보여주고 싶을 때

```html
<a href="https://www.google.com">GOOGLE</a>
```

```bash

$ git commit -m "Study MarkDown"
```

```plaintext

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세

```

# 표(Table)

position 속성

| 값       | 의미              | 기본값 |
| -------- | ----------------- | ------ |
| static   | 기준 없음         | O      |
| relative | 요소 자신         | X      |
| absolute | 위치 상 부모 요소 | X      |
| fixed    | 뷰포트            | X      |

<!-- 가운데 정렬 -->

|    값    |       의미        | 기본값 |
| :------: | :---------------: | :----: |
|  static  |     기준 없음     |   O    |
| relative |     요소 자신     |   X    |
| absolute | 위치 상 부모 요소 |   X    |
|  fixed   |      뷰포트       |   X    |

<!-- 우측 정렬 -->

|       값 |              의미 | 기본값 |
| -------: | ----------------: | -----: |
|   static |         기준 없음 |      O |
| relative |         요소 자신 |      X |
| absolute | 위치 상 부모 요소 |      X |
|    fixed |            뷰포트 |      X |

  <br/>
  
# 원시 HTML(Raw HTML)

<u>**동해물**</u>과 <span style="text-decoration: underline; color: pink">**백두산**</span>이 마르고 닳도록<br/>
하느님이 보우하사 우리나라 만세

---

# 수평선

---

---

---
