# 블로그 운영 (자주 쓰는 기능)

<https://kingmandooo.github.io>

**github Actions를 통해 블로그에 언제 배포되는 지를 확인 할 수 있음**

---

_pagaes 안에 category-cpp.md 파일을 만들었고
이는 cpp 카테고리를 뜻한다.

그리고 _include 파일 안에 있는
nav_list_main에서 카테고리를 만들어주면 된다.

주의할 점은 nav_list_main의 카테고리와 포스팅 파일에서 정해준 카테고리의 이름이
같아야 한다는 것이고,
경로를 올바르게 지정해주어야 한다는 것이다.

포스팅은 _posts 파일 안에서 .md 파일로 작성해주면 된다.

---

### 포스팅 
```
---
layout: single

title: "My first posting!!"      # 제목

categories: 잡담                 # 카테고리 분류 기능

tag: [blog, jekyll]              # 태그 분류 기능 ( 다른 예시 --> tag: C )

author_profile: true             # 왼쪽 프로필 보이기 여부

sidebar:                         # 왼쪽 사이드바
     nav: "docs"

search: false                    # 포스팅 검색 가능 여부 기능
---
```

### 공지사항 추가 & 목차
```
<!-- 베너형식 공지사항 -->
**[공지사항]** [이 블로그는 만들어지는 중.. danger](https://kingmandooo.github.io/minimal-mistakes/docs/quick-start-guide/)
{: .notice--danger}  

**[공지사항]** 이 블로그는 만들어지는 중.. success
{: .notice--success}  

**[공지사항]** 이 블로그는 만들어지는 중.. primary
{: .notice--primary}  

**[공지사항]** 이 블로그는 만들어지는 중.. info
{: .notice--info}  

**[공지사항]** 이 블로그는 만들어지는 중.. warning
{: .notice--warning}  

**[공지사항]** 이 블로그는 만들어지는 중.. default
{: .notice}

<!-- div로 감싸서 리스트로 만든 공지 -->
<div class="notice--success">  
    <ul>
        <li>공지1</li>
        <li>공지2</li>
        <li>공지3</li>
    </ul> 
</div>

# Part 1

## 목차들

### 세부 목차 1

안뇽111

### 세부 목차 2

안뇽222
```

### 버튼 추가
```
<!-- [Text](#link){: .btn .btn--danger}   버튼 추가하기 링크 칸에 링크 써놓기 -->
[YouTube](https://youtube.com){: .btn .btn--danger}
```

### 이미지 올리기
```
(참고로 .img-width-half는 유튜브보고 따로 만든 기능)

<!-- 이미지 크기 조정 (가운데 정렬까지 추가) //  .align-left, .align-right 기능 또한 있음-->
![kingmandooo](/assets/images/kingmandooo.png){: .img-width-half .align-center}  
```

### LaTex 수식 문법을 지원하는 mathjax 블로그에 적용 
```
use_math: true # 수학 수식 사용

예시)  $\[ x^n + y^n = z^n \]$
       $y = f(x)^2$

```
