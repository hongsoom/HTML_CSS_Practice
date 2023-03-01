## Media-Query

### 반응형 웹 Responsive Web

요즘에는 웹 브라우저를 여러 사이즈의 디바이스를 통해 사용

**디바이스의 사이즈에 따라** 그에 맞게 화면을 보여지기 위해

CSS 스타일을 적용해 놓은 웹 사이트

### ① viewport meta - `HTML`

```HTML
<!DOCTYPE html>
<html>
    <head>
        <meta name="viewport" content="width=device-width" />
        ...
    </head>
</html>
```


### ② media query - `CSS`

```CSS
@media screen and (min-width: 768px) {
    // 가로 길이가 768px 이상일 때
}

@media screen and (min-width: 768px) and (max-width: 991px) {
    // 가로 길이가 768px 이상이고 991px 이하일 때
}
```

➕ `vh` `vw`
 
viewport의 얼마를 차지할까
    
    ex) 1vh : 전체화면의 1%만 차지 
        100vh : 전체화면의 전체를 차지





