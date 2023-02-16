## Logo in Header

### Screenshot
<img src="./Logo-in-Header.PNG" alt="헤더">

### 배운 내용
페이지 전체의 제목인데 텍스트가 아니고 이미지일 경우,
먼저 `h1` 태그로 묶는데 해당 이미지가 정보 컨텐츠의 가치가 있느냐?!를 따져봤을 때 의미가 있을 경우
- 사이트 전체를 대표하는 로고
- 브랜드의 identity

but, 아래 처럼 `h1`태그를 사용하고 `img`태그를 사용한다면은
`h1`를 css처리를 해줘야하는 번거러움이 생김
```HTML
<h1> Goorm Edu
     <img src="https://statics.goorm.io/logo/edu/goorm_edu.svg" alt="" />
</h1>
```

이럴 때 사용할 수 있는게 `img`태그의 `alt`속성
텍스트를 생략하고 alt 값으로 대체할 수 있다.
아래처럼 하면 이미지 로고도 잘 나오고 브라우저도 인식을 잘함
```HTML
<h1>
     <img src="https://statics.goorm.io/logo/edu/goorm_edu.svg" alt="Goorm Edu" />
</h1>
```
