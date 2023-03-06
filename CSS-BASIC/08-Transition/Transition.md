## Transition
변화가 확 바뀌는게 아니라 자연스럽게 스르륵 변화하기 위해 사용

### ① property
변화할게 어떤것인지 명시

### ② duration
지속시간

- ms
    1,000ms === 1s

- s

```CSS
.box {
    transition : font-size 2500ms;
    transition : all 2500ms;
}

.box.active {
    font-size : 30px;
    background-color : #ff4949;
}
```

### ③ [timing-function] - 생략가능
변화의 속도

```CSS
.box {
    transition : all 2500ms ease-in;
    /* ease-in | ease-out | ease-in-out | cubic-bezier() */
}
```

- ease-in
    처음 천천히 나중에 휙

- ease-out
    처음 휙 나중에 천천히

- ease-in-out

- cubic-bezier()
    커스텀 
    https://cubic-bezier.com/#.17,.67,.83,.67


### ④ [delay] - 생략가능
나중에 변화시키고 싶을 때 사용

```CSS
.box {
    transition : all 2500ms ease-in 1000ms;
}
```

### ⑤ 개별 선언 가능
```CSS
.box {
    transition : font-size 2500ms ease-in, background-color 200ms ease-out 1000ms;
}
```