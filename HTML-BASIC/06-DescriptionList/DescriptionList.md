## 정의 리스트 Description List

```HTML
용어를 정의하거나 Key-Value로 정보를 제공할 때 사용하는 태그 <dl>
<dl>
    <dt>용어</dt>
    <dd>설명</dd>
</dl>

<dl>태그의 자식요소는 <div> <dd> <dt>만 올 수 있다.
<dd> <dt>는 단독으로 사용 불가능하다.

➕ <dfn>
용어를 정의한다고 더 강조하는 태그
```

### 예시)
<h1>Good</h1>
```HTML
<dl>
    <dt>홍수민</dt>
    <dd>주니어 개발자</dd>
</dl>

<dl>
    <dt>
        <dfn>development</dfn>
    </dt>
    <dd>1. [U] 발달, 성장</dd>
    <dd>2. [U, C] (신제품의) 개발; 신개발품</dd>
</dl>

<dl>
    <dt>홍수민</dt>
    <dt>Hongsumin</dt>
    <dd>주니어 개발자</dd>
</dl>

<dl>
    <dt>홍수민</dt>
    <dd>주니어 개발자</dd>
    <dd>
        <a href="https://github.com/hongsoom">홍수민 깃허브</a>
    </dd>
</dl>

<dl>
    <div>
        <dt>사과</dt>
        <dd>사과에 대한 설명</dd>
    </div>
    <div>
        <dt>바나나</dt>
        <dd>바나나에 대한 설명</dd>
    </div>
</dl>
```
<h1>Bad</h1>
```HTML
<dl>
    <dt>홍수민</dt>
    <dd>주니어 개발자</dd>
    <dt>데벨업</dt>
    <!-- 데벨업에 대한 정의가 빠졌다-->
</dl>

<!-- dl의 자식요소는 오직 div, dt, dd만 가능-->
<dl>
    <section>
        <dt>홍수민</dt>
        <dd>주니어 개발자</dd>
    </section> 
</dl>

<!-- dt와 dd는 반드시 dl의 자식요소로 존재해야 한다-->
<dt>홍수민</dt>
```