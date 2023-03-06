## Background

### ① background-color
배경 색

- hex

- rgb

- rgba


### ② background-image
배경 이미지

```CSS
.text {
    background-image: url('./~~~.png');
    background-image: url('https//~~~');
}
```

### ③ background-repeat

```CSS
.text {
    background-repeat: repeat;
    /* repeat | no-repeat */
}
```

- repeat
    `background-image`를 사용하면 반복적으로 이미지가 나옴

- no-repeat
    반복 NO

### ④ background-size
image의 크기

```CSS
.text {
    background-size: contain;
    /* contain | cover | custom */
}
```

- contain
    요소안에 이미지 전체 다 들어갈 수 있음

- cover
    요소안에 빈공간이 남지 않도록 꽉 차게    

- custom
    커스텀 - 잘 사용안함

### ⑤ background-position
image를 어디에다 위치 시킬지

```CSS
.text {
    background-position: center center;
    /* x축 y축 다 적어줘야함 
        50% 50%, left top, 10px 30px ...
    */
}
```