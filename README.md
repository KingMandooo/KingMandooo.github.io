# 블로그 운영 (자주 쓰는 기능)

**github Actions를 통해 블로그에 언제 배포되는 지를 확인 할 수 있음**

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

### 공지사항 추가
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
