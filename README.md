# 블로그 운영

### 자주 쓰는 기능

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
