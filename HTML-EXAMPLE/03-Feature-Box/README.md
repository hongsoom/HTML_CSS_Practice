## Feature Box

### Screenshot
<img src="./Feature-Box.PNG" alt="Feature Box">

### 배운 내용
만약, 이미지가 내용에 별로 중요하지 않다고 느껴 img 태그가 불필요 하다고 생각한다면,
img 태그를 사용하지 않고 css를 통해 이미지를 보여줄 수 있다.

```CSS
<div class="feature-box no-image">

.feature-box.no-image {
    padding-top: 196px;
    background-image: url("https://wac-cdn.atlassian.com/dam/jcr:bc1f15f9-3b2e-4c30-9313-0ebd6175f18c/File%20Cabinet@2x.png?cdnVersion=676");
    background-repeat: no-repeat;
    background-position: center 40px;
    background-size: auto 140px;
}
```