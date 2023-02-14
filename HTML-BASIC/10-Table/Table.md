## Table

```HTML
데이터를 담은 표를 만들 때 사용하는 태그
<table>
    <tr>
        <th>테이블 헤더</th>
        <td>테이블 데이터</td>
    </tr>
</table>

th가 5개면 td도 무조건 5개여야 한다.
만약 들어갈 데이터가 없다면 빈태그라도 작성해야 한다.

➕ <thead> <tbody> <tfoot>
    머리, 본문, 바닥을 명시해주는 태그
  <thead>
        <tr>
            <th>ID</th>
            <th>이름</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>hongsoom</td>
            <td>홍수민</td>
        </tr>
    </tbody>

➕ rowspan, colspan
rowspan = "숫자" : 행으로 차지하는 개수
colspan = "숫자" : 열로 차지하는 개수

➕ scope
scope = "row/col" : 세로줄의 헤더인지, 가로줄의 헤더인지 명시해주는 역할
테이블 헤더에게만 사용 가능
```

### 예시)
<table>
    <thead>
      <tr>
        <th></th>
        <th>월</th>
        <th>화</th>
        <th>수</th>
        <th>목</th>
        <th>금</th>
      </tr>
    </thead>
    <tbody>
        <tr>
            <th>1교시</th>
            <td rowspan="2">왕초보 HTML &amp; CSS</td>
            <td>모각코</td>
            <td rowspan="2">왕초보 HTML &amp; CSS</td>
            <td>모각코</td>
            <td rowspan="2">왕초보 HTML &amp; CSS</td>
        </tr>
        <tr>
            <th>2교시</th>
            <td rowspan="2">JavaScript 스킬업</td>
            <td rowspan="2">JavaScript 스킬업</td>
        </tr>
        <tr>
            <th>3교시</th>
            <td>JavaScript 시작반</td> 
            <td>JavaScript 시작반</td> 
            <td>JavaScript 시작반</td> 
        </tr>
        <tr>
            <th colspan="6">점심시간</th>
        </tr>
        <tr>
            <th>4교시</th>
            <td>SASS 기초반</td>
            <td rowspan="2">HTML &amp; CSS 포토폴리오반</td>
            <td rowspan="2">Open Semin ar</td>
            <td rowspan="2">HTML &amp; CSS 포토폴리오반</td>
            <td>SASS 기초반</td>
        </tr>
        <tr>
            <th>5교시</th>
            <td>모각코</td>
            <td>모각코</td>
      </tr>
    </tbody>
</table>

```HTML
<table>
    <thead>
      <tr>
        <th></th>
        <th>월</th>
        <th>화</th>
        <th>수</th>
        <th>목</th>
        <th>금</th>
      </tr>
    </thead>
    <tbody>
        <tr>
            <th>1교시</th>
            <td rowspan="2">왕초보 HTML &amp; CSS</td>
            <td>모각코</td>
            <td rowspan="2">왕초보 HTML &amp; CSS</td>
            <td>모각코</td>
            <td rowspan="2">왕초보 HTML &amp; CSS</td>
        </tr>
        <tr>
            <th>2교시</th>
            <td rowspan="2">JavaScript 스킬업</td>
            <td rowspan="2">JavaScript 스킬업</td>
        </tr>
        <tr>
            <th>3교시</th>
            <td>JavaScript 시작반</td> 
            <td>JavaScript 시작반</td> 
            <td>JavaScript 시작반</td> 
        </tr>
        <tr>
            <th colspan="6">점심시간</th>
        </tr>
        <tr>
            <th>4교시</th>
            <td>SASS 기초반</td>
            <td rowspan="2">HTML &amp; CSS 포토폴리오반</td>
            <td rowspan="2">Open Semin ar</td>
            <td rowspan="2">HTML &amp; CSS 포토폴리오반</td>
            <td>SASS 기초반</td>
        </tr>
        <tr>
            <th>5교시</th>
            <td>모각코</td>
            <td>모각코</td>
      </tr>
    </tbody>
</table>
```