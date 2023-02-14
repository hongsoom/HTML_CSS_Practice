## Media 태그들

### ① audio
음성 파일을 넣고 싶을 때 사용하는 태그
```HTML
<audio src="./~~~~~"></audio>
```
- src
필수로 적음

- controls
재생버튼, 음향조절
이걸 안쓰면 아예 안보임(흰화면)

- autoplay
페이지 들어가자마자 자동 재생
  - loop autoplay : 무한반복 재생

- 사용자들이 어떤 브라우저를 사용할 지 모르기 때문에 최대한 지원
(type은 모를 때는 구글에서 찾아보기)
```HTML
<audio controls>
  <source src="~/wav" type="audio/wav"/>
   <source src="~/mp3" type="audio/mpeg"/>
   <source src="~/ogg" type="audio/ogg"/>
   <p>현재 사용하시는 브라우저에는 지원이 불가능 합니다.</p>
</audio>
```

### ② video
비디오 파일을 넣고 싶을 때 사용하는 태그 
문법은 audio와 동일!

```HTML
<video src="./~~~~~"></video>
```

- src
필수로 적음

- controls
재생버튼, 음향조절
이걸 안쓰면 아예 안보임(흰화면)

- autoplay
페이지 들어가자마자 자동 재생
  - loop autoplay : 무한반복 재생

- 사용자들이 어떤 브라우저를 사용할 지 모르기 때문에 최대한 지원
(type은 모를 때는 구글에서 찾아보기)
```HTML
<video controls>
   <source src="~/mov" type="video/mp4"/>
   <source src="~/mp4" type="video/mp4"/>
   <p>현재 사용하시는 브라우저에는 지원이 불가능 합니다. </p>
</video>
```

### ③ iframe
또 다른 HTML 문서(컨텐츠)를 넣고 싶을 때 사용 ex) 유튜브 동영상
```HTML
<iframe src="넣고 싶을 HTML 문서" frameborder="0"></iframe>
```
