## Form 폼

```HTML
사용자로부터 정보와 데이터를 받기 위한 태그
<form action="API 주소" method="GET/POST">
```

### 폼 안에 다양한 필드 태그들
### ① input
```HTML
<input type="text, email, password, url, number, tel, file, radio, checkbox">
`type`속성은 꼭 써줘야한다.
`type`속성에는 text, email, password, url, number, tel, file, radio, checkbox 등 다양한 type이 있다.

type이 password일 경우, 입력한게 보이지 않게 ·····로 바뀐다.
type이 number일 경우, min 최소 값 max 최대 값 속성이 있다.
type이 file일 경우, accept 속성을 통해 들어올 확장자를 지정해준다.

➕ 많이 사용하는 속성들
placeholder : 값이 없을 때 기본으로 보여주는 것
maxlength : 길이 제한 최대
minlength : 길이 제한 최소
required : 무조건 입력을 해야 함 (명시하면 true 명시하지 않으면 false)
disabled : 사용 못하게 막음  (명시하면 true 명시하지 않으면 false)
value : 초기 값
```

### ② label
input의 대한 이름 
```HTML
<label for="input id">라벨</label>
`for`속성은 꼭 적어야 한다.

ex)
<label for="apple"></label>
<input id="apple" type="text" />
```

### ③ Radio & Checkbox
Radio : 둘 중 하나만 선택
Checkbox : 다중 선택
➡ 문법은 둘 다 동일!

```HTML
<label for="on">click</label>
<input type="radio" id="on" name="radio name" value="on" />

<label for="off">click</label>
<input type="radio" id="off" name="radio name" value="off" />

`name`속성은 radio에서 꼭 적어줘야 하는 이유?
둘 중 하나를 선택해야 하기 때문에 만약 없을 시 두개 다 선택이 가능하게 됨
그래서 name은 연관이 있는 목록끼리 똑같은 name를 가지게 된다.

`value`속성은?
서버에 전달할 때 어떤 것이 왔는지 구분하기 위해 value를 꼭 적어줘야 한다.
```

### ④ Select & Option
옵션 메뉴를 제공하는 태그
➡ radio, checkbox와 name, value 문법 동일!
```HTML
<select name="select">
    <option value="HTML">HTML</option>
    <option value="CSS">CSS</option>
    <option value="JS">JavaScript</option>
</select>

`name`속성을 select에 써주면 자식 요소인 option들에게 당연히 적용된다.
`mutiple`속성은 여러개를 선택할 수 있게 해주는 속성이다. (select 태그에 적어주면 됨)
```

### ⑤ Textarea
여러줄을 가능하게 해주는 태그 <-> input type text는 간단한 한줄만
```HTML
<textarea></textarea>
`rows`, `cols` 속성 : 가로, 세로 보이는 영역의 라인수를 명시하는 속성
하지만, CSS에서 height 속성과 width 속성으로 설정이 가능!
```

### ⑥ Buttons
클릭할 수 있는 버튼을 정의할 때 사용
```HTML
<button type="button, submit, reset"></button>
`button` : 버튼
`submit` : 폼 제출
`reset` : 폼 리셋
```
