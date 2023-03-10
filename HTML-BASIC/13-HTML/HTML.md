## HTML (HyperText Markup Language)
웹 문서 만들기 위해 만들어진 언어

## HTML의 기본 구조
```HTML
<!docutype html> 
<html>
	<head>
		<!-- 웹 문서에 관한 메타 데이터 -->
	</head>
	<body>
		<!-- 웹 문서에 들어갈 내용 -->
	</body>
</html>
```

### ① <!docutype html>
html 버전 선언, HTML이 어떤 버전으로 작성되었는지 미리 선언해 웹 브라우저가 내용을 올바로 표시 할 수 있도록 해주는 것

### ② head 태그
브라우저 화면에 직접적으로 보이지 않으며, 숨은 데이터를 정의하는 태그들이 선언

```HTML
<title>제목</title>
웹페이지의 제목, 브라우저의 탭에서 확인 할 수 있다. 
유저에게 문서의 제목을 알리는 용도 뿐만 아니라, 검색 엔진 등에서 가장 크게 보여지는 텍스트이므로 페이지의 특성을 드러내는 제목을 작성하는 것이 중요하다.

<link>
css 스타일시트를 첨부할 때 사용하는 태그

<style></style>
HTML 문서내에 CSS 코드를 작성할 때 사용하는 태그

<meta name="메타데이터 종류" content="메타데이터 값">
meta 태그는 HTML 문서가 어떤 내용을 담고 있고, 키워드는 무엇이며, 누가 만들었는지에 대한 정보를 담고있는 태그
```

### ③ body 태그
브라우저화면에 보이는 것들이 주로 들어간다.

```HTML
<script src="경로"></script>
body내에서 가장 마지막에 작성하는 것이 제일 좋다
HTML 문서내에 JavaScript 파일을 첨부할 때 사용하는 태그
```