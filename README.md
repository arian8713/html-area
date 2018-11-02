## 1. meta 태그 알아보기

meta 태그는 meta 데이터를 제공하기 위해 사용되며 사이트의 정보를 제공함이 가장 큰 목적이다.

- 사용법
```
<html>
  <head>
    <title>Meta 태그 알아보기</title>
    <meta charset="utf-8">
    <meta name="keyword" content="meta, tag, html">
  </head>
  <body>
    ...
  </body>
</html>
```

위와 같이 meta 태그는 HTML의 HEAD 태그 안에 작성하며
meta 라는 단일 태그(single tag) 안에 속성명과 속성값을 넣어서 사용한다.

사용 조건, 방법은 위와 같이 매우 단순하니 어떠한 속성을 가지고 있고 사용 용도에 대해 알아보도록 하자.

```
<html>
  <head>
    <title>Meta 태그 알아보기</title>
    <meta charset="utf-8">
    <meta name="keyword" content="해당 사이트의 키워드">
    <meta name="Description" content="해당 사이트를 설명하는 글">
    <meta name="robots" content="로봇의 검색을 제어"> <!-- ex: "noindex, follow" -->
    <meta name="author" content="저자, 제작자">
    <meta name="viewport" content="해당 사이트의 화면 영역을 조절"> <!-- ex: "width=device-width" -->
    <meta http-equiv="X-UA-Compatible" content="IE=edge" /> <!-- browser의 호환성을 지정 -->
  <body>
    ...
  </body>
</html>
```

위에 여러가지 속성명과 속성값을 작성하였는데 주로 사용되는 요소를 작성하였고 이후에 필요한 속성이 있을 경우
검색을 참고하면 좋을 것 같다. meta에 대한 자세한 설명은 생활코딩보다 좋은 설명이 없어서 생활코딩을 참고하였다.


#### 속성
name : 문서의 메타데이터를 설정합니다.
http-equiv : 전처리 구문 지시자입니다.
content : name속성이나 http-equiv속성을 사용했을 때 함께 명시합니다.
charset : 문자 인코딩 방식을 명시합니다.

#### 설명
name, http-equiv, charset 속성중 하나만 사용할 수 있습니다.
만약 name이나 http-equiv중 하나를 사용했다면 반드시 content속성을 사용해야 합니다. 그렇지 않으면 그것들은 생략되어야 합니다.
한 문서에서 charset속성을 가진 하나의 meta속성만 사용할 수 있습니다.




