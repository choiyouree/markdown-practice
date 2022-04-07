# 제목(Header)

# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6

# 문장 (Paragraph)

<!-- 줄바꿈 처리를 자동으로 해주지 않는다.-->

# 줄바꿈 (Line Breaks)

동해물과  백두산이  마르고  닳도록  
하느님이  보우하사  우리나라  만세  
무궁화 삼천리<br> 
화려 강사  
대한 사람 대한으로 길이 보전하세
<!-- 띄어쓰기 두번 눌러서 줄바꿈 가능 -->

# 강조 (Emphasis)

_이텔릭_  
**두껍게**  
**_이텔릭두껍게_**  
~~취소선~~  
<u>밑줄</u>

# 목록(List)
1. 순서가 필요한 목록  
     1.순서가 필요한 목록  
     1.순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
<!-- 직접 순서를 넣지 않아도 자동으로 만들어짐 -->
<!-- 들여쓰기 두번하면 소제목을 넣듯이 작은 내용 넣을 수 있음 -->
- 순서가 필요하지 않은 목록  
    - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
<!-- 하이픈 점 기호로 목록을 나타내는 -->
<!-- 들여쓰기 2번 하이픈 점기호로 소제목 넣듯 작은 내용 넣을 수 있음 -->

# 링크(Link)

<a href="http://google.com">GOOGLE</a>  
[GOOGLE](http://google.com)  
<a href="http://naver.com">NAVER</a>   
[NAVER](http://naver.com "NAVER로 이동!")

# 이미지 (Image)

![HEROPY](https://heropy.blog/css/images/logo.png)

<!-- 이미지에 링크되게 -->
[![HEROPY](https://heropy.blog/css/images/logo.png)](https://heropy.blog/)

# 인용문(BlockQuote)

>남의 말이나 글에서 직접 또는  
>간접으로 따온 문장.(네이버 국어 사전)

>인용문을 작성하세요!
>> 중첩된 인용문
>>> 중중첩된 인용문 1
>>> 중중첩된 인용문 2
>>> 중중첩된 인용문 3

# 인라인(inline) 코드 강조

css에서 `background` 혹은  
`background-image` 속성으로   
요소에 배경 이미지를 삽입할 수 있습니다.

# 블록(block) 코드 강조

```html
<a href="http://www.google.co.kr/" target="_blank">GOOGLE</a>
```
```css
.list > li {
  positon: absolute;
  top: 20px;
}
```

#표 (table)

positon 속성

값 | 의미 | 기본값
--:|:--:|--
static | 기준 없음 | 0
relative | 요소 자신 | X
absolute | 위치 상 부모요소 | X
fixed | 뷰포트 | X

# 원시 HTML (Raw HTML)

동해물과 <u>백두산</u>이 마르고 닳도록  
<span style="text-decoration: underline;">하느님</span>이 보우하사 우리나라 만세

<a href= "http://naver.com" title="NAVER로 이동!" target="_blank">NAVER</a>

<img width="70" src="https://heropy.blog/css/images/logo.png">

<!-- html에서 쓰는 코드들을 활요하여 마크 다운에서 활용할 수 있다 -->

# 수평선(Horizontal Rule)
---
***
___