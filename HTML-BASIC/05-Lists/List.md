## 목록 List

```HTML
목록을 나타내는 태그 <ul> <ol>
<ul> 순서가 중요하지 않은 목록 - 번호가 붙지 않는
<ol> 순서가 중요한 목록 - 번호가 붙는 

<ul>와 <ol> 안에는 꼭 <li>만 들어올 수 있다.
<div> <a> 태그들은 ❌
만약 사용하고 싶다면 
<ol> 
    <li> 
        <a> 
    </li>
</ol> 처럼 <li> 안에다 적어줘야 한다.

➕ ·을 없애기 위한 css 
list-style-type : none; 
```

### 예시)

<h1>개발</h1>
<ul style="list-style-type : none;">
    <li>웹 개발자</li>
    <li>서버 개발자</li>
    <li>프론트엔드 개발자</li>
    <li>자바 개발자</li>
    <li>안드로이드 개발자</li>
    <li>iOS 개발자</li>
    <li>파이썬 개발자</li>
    <li>시스템,네트워크 개발자</li>
</ul>

```HTML
<h1>개발</h1>
<ul style="list-style-type : none;">
    <li>웹 개발자</li>
    <li>서버 개발자</li>
    <li>프론트엔드 개발자</li>
    <li>자바 개발자</li>
    <li>안드로이드 개발자</li>
    <li>iOS 개발자</li>
    <li>파이썬 개발자</li>
    <li>시스템,네트워크 개발자</li>
</ul>
```

<h1>급상승 검색어</h1>
<ol>
    <li>김버그</li>
    <li>프론트엔드 개발</li>
    <li>구름</li>
    <li>주니어개발자</li>
    <li>Goorm</li>
    <li>Frontend</li>
    <li>개발</li>
    <li>구름IDE</li>
    <li>버그 킴</li>
    <li>튕김버그</li>
</ol>

```HTML
<h1>급상승 검색어</h1>
<ol>
    <li>김버그</li>
    <li>프론트엔드 개발</li>
    <li>구름</li>
    <li>주니어개발자</li>
    <li>Goorm</li>
    <li>Frontend</li>
    <li>개발</li>
    <li>구름IDE</li>
    <li>버그 킴</li>
    <li>튕김버그</li>
</ol>
```