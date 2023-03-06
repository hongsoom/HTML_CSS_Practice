## Typography

### 속성
### ① font-size
글씨 크기

```CSS
.text {
    font-size : 16px;
}
```

- px
    절대 단위(고정)

- em (equal to capital M)
    상대 단위
    실제로 적용된 폰트 사이즈 기준
    ```HTML
    <div class="parent">
        <p>예시입니다.</p>    
    </div>
    ```
    ```CSS
    .parent {
        font-size : 20px;
    }

    .p {
        font-size : 1.5em; // 30px 
        /* 즉 1em = 20px */
    }
    ```

- rem (root em)
    상대 단위
    HTML 기준
    ```CSS
    html {
        font-size : 20px;
    }

    .p {
        font-size : 3rem; // 60px 
        /* 즉 1em = 20px */
    }
    ```

### ② line-height
줄 간격

글자는 가장 가운데에 배치

```CSS
.text {
    font-size : 16px;
    line-height : 1.5;
}
```

- px

- em 
    **가장 많이 사용**
    폰트 사이즈와 비례
    `em`를 생략해도 괜찮음

- rem

### ③ letter-spacing
글자 간격

```CSS
.text {
    font-size : 16px;
    line-height : 1.5;
    letter-spacing : -.03em;
}
```

- px
    
- em 
    **가장 많이 사용**
    폰트 사이즈와 비례
### ④ font-family
폰트 서체

```CSS
.text {
    font-family : "Poppins";
    font-family : "Poppins", sans-serif;
    font-family : "Poppins", "Roboto", sans-serif;
    /*
        Poppins와 Roboto가 없다면 sans-serif 서체중 아무거나 써줘!
    */
}
```

### ⑤ font-weight
폰트 굵기

```CSS
.text {
    font-size : 16px;
    line-height : 1.5;
    letter-spacing : -.03em;
    font-family : "Poppins", sans-serif;
    font-weight : 400;
    /* 100 | 200 | 300 | 400 | 500 | 600 | 700 | 800 | 900 */
}
```
- Regular = 400

- Bold = 700

- Light = 300

### ⑥ color
글자 색상

```CSS
.text {
    font-size : 16px;
    line-height : 1.5;
    letter-spacing : -.03em;
    font-family : "Poppins", sans-serif;
    font-weight : 400;
    color : #0061ff;
}
```

- hex
    `#0066ff`

- rgb
    `rgb(0, 102, 255)`

- rgba
    `rgba(0, 102, 255, 1)`

    - 1 완전 불투명
   
    - 0 완전 투명
    
    - 0.5 50% 투명

### ⑦ text-align
글자 정렬

```CSS
.text {
    text-align : left | right | center;
}
```

### ⑧ text-indent
들여 쓰기

```CSS
.text {
    text-indent : 100px
    /* 음수도 가능*/ 
}
```

### ⑨ text-transform
알파벳만 가능

```CSS
.text {
    text-transform : none;
    /* none | capitalize | uppercase | lowercase */
}
```

- none
    기본 상태

- capitalize
    앞자리만 대문자
    `Hong Su Min`

- uppercase
    모든 글자가 대문자
    `HONG SU MIN`

- lowercase
    모든 글자가 소문자
    `hong su min`

### ⑩ text-decoration
줄 긋기

```CSS
.text {
    text-decoration : none;
    /* none | underline | line-throught | overline */
}
```

- none
    줄 NO

- underline
    밑줄 생김

- line-throught
    글자 가운데로 줄이 생김

- overline
    글자 위로 줄이 생김


### ⑪ font-style
글자 기울기

```CSS
.text {
    font-style : normal;
    /* normal | italic | oblique */
}
```
