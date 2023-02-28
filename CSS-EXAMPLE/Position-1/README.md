## Position 훈련 1

### Screenshot
<img src="./assets/absolute.PNG" alt="absolute 예제"/>

### 배운 내용

`img`태그는 원래 inline 요소 이지만

왜 width, height 속성이 먹히는가 ?

원래 파일 자체가 가지고 있는 사이즈 때문에 `width`, `height`를 가지게 됨

그렇지만 명시적으로 하기 위해서는

`display : block`이라고 써주는것이 좋다.

하지만 `position: absolute`를 사용한다면 `block`이 되기 때문에

생략이 가능

```CSS
.user-status {
    position: absolute;
    right: 0;
    bottom: 0;
    width: 12px;
    height: 12px;
    border-radius: 50%;
    border: 2px solid #fff;
    background-color: #21D891;
}

.user-status {
    display: block;
    width: 8px;
    height: 8px;
    border-radius: 50%;
    border: 2px solid #fff;
    background-color: #21D891;
    box-sizing: content-box;
}
```