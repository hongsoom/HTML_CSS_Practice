## Float 훈련 1

### Figma 디자인 시안
https://www.figma.com/file/k6aekBk53MUKUwVqRHsSVx/Bugless-CSS?node-id=0%3A1

### Screenshot
<img src="./assets/float1.PNG" alt="float1">

### 배운 내용
```HTML
<li class="tab-menu-item">
    <a href="#">Mentions</a>
</li>
```
글씨를 눌러야 이동하는 것은 너무 좁은 범위이기 때문에

사용자의 편의성을 위하여 a 태그에 padding을 넣어 글씨가 아닌

li 태그 안에 있는 다른 곳을 눌러도 이동이 되게끔 padding을 넣어준다.

하지만 a 태그는 inline이기 때문에 padding을 줄 수 없음

```CSS
.tab-menu-item a {
    display: block;
    padding: 16px 20px;
}
```