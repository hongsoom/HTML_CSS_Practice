## Float
주로 레이아웃을 구성할 때 `블록 레벨 요소`를 **가로 정렬**하기 위해 사용되는 중요한 기법

요소가 기본 레이아웃 흐름에서 벗어나 요소의 모서리가 페이지의 왼쪽이나 오른쪽에 이동하는 것

### ① Float란?
<img src="./assets/Float1.PNG" alt="float예시" />

<img src="./assets/Float2.PNG" alt="float예시" />

<img src="./assets/Float3.PNG" alt="float예시" />

빨간 박스가 Float : left;를 하면은 부모는 요소가 없다고 생각하여 즉, 빈공간이라 생각하여 뒤에 나머지 요소를 앞으로 채우기 시작한다.

그 후, 자식은 노랑, 파랑 밖에 없다고 인식하고 비어있는 공간을 유지할 필요가 없으니 자식 요소에 맞게 줄어든다.

### ② block?????

어느 한 박스에 Float를 먹인다면 그 박스는 `block`이 된다.

이 말은 block이 할 수 있는 모든 것들을 다 할 수 있다.

예시) inline인 span 태그인 박스 중 빨간 박스에게 float : left를 준다면?

<div style="background-color: #eff2f7; margin: 0 auto; width: 200px;">
    <span style="background-color: red
    ; text-align: center; color: #fff; font-weight: 900;">Child
    </span>
    <span style="background-color: yellow
    ; text-align: center; color: #fff; font-weight: 900;">Child</span>
    <span style="background-color: blue
    ; text-align: center; color: #fff; font-weight: 900;">Child</span>
</div>

```CSS
빨강 박스에 float: left;를 준 경우
```
<div style="background-color: #eff2f7; margin: 0 auto; width: 200px;">
    <span style="background-color: red
    ; text-align: center; color: #fff; font-weight: 900; float: left;">Child
    </span>
    <span style="background-color: yellow
    ; text-align: center; color: #fff; font-weight: 900;">Child</span>
    <span style="background-color: blue
    ; text-align: center; color: #fff; font-weight: 900;">Child</span>
</div>

```CSS
빨강 박스에 float: left; width: 100%; height: 200px;를 준 경우
```
<div style="background-color: #eff2f7; margin: 0 auto; width: 200px;">
    <span style="background-color: red
    ; text-align: center; color: #fff; font-weight: 900; float: left; width: 100%; height: 200px;">Child
    </span>
    <span style="background-color: yellow
    ; text-align: center; color: #fff; font-weight: 900;">Child</span>
    <span style="background-color: blue
    ; text-align: center; color: #fff; font-weight: 900;">Child</span>
</div>