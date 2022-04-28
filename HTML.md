# HTML

### HTML(Hypertext Markup Language)란?

- HTML란 웹브라우저 상에서 보여지도록 설계된 문서이며 , 표준화된 markup 언어를 사용한다
- Markup Language : 일반적인 텍스트와 문법적으로 구분하기 위해서 문서에  annotating 된 것

- 현재는 HTML5 버전을 사용 하고 있다!
- 공식사이트 [https://developer.mozilla.org/ko/docs/Web/HTML/Element]

### Tag & Element

```
-Tag <p> </p>
-content : ABCDEFG
-Element(요소,노드) : <p> ABCDEFG</p>
```

### Attribute(속성)

```
<p class='editor-note'> ABCDEFG </p>
<p id=""> ABCDEFG </p>
```

- tag 내 class , id 등 추가적인 내용을 정의하여 style을 적용하거나 js로 요소를 찾을때 사용됨

### HTML a tag(앵커요소)

- href 특성을 통해 다른페이지나 같은 페이지의 어느 위치,파일,이메일 주소와 그 외 다른URL로 연결할 수 있는 하이퍼 링크 생성
- <a> 안의 콘텐츠는 링크 목적지의 설명을 나타내야함

```
<a href="https://google.com" target='_blank'>Click Me!</a>


<ul>
  <li><a href="https://example.com">Website</a></li>
  <li><a href="mailto:m.bluth@example.com">Email</a></li>
  <li><a href="tel:+123456789">Phone</a></li>
</ul>
```

### HTML Styling

```
<body style="background-color:lightgrey">


<h1 style="color:blue">This is a heading</h1>
<p style="color:red">This is a paragraph.</p>


<h1 style="text-align:center">


  <style>
  p {
    margin: 10px 0;
    padding: 5px;
    border: 1px solid #999;
   }
  </style>
```

