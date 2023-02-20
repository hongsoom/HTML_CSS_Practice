### Sectioning Elements
#### section 
섹션(부분, 구역, 영역) 들을 그룹화 해서 분리하는 역할


#### article 
뉴스기사, 블로그 등 문서내에서 그룹화해서 분리하는 역할


#### nav 
문서간 이동할 수 있는 메뉴가 있을 때


#### aside 
본문 내용과 직접적으로 관련이 없는 동 떨어진 분리된 내용을 마크업할 때(위젯, 배너, sidebar)

### Sectioning Elements들이 공통적으로 지켜야 할 룰
Sectioning Elements 내에서는 반드시 `heading`태그를 작성해야 한다
-> 정보를 좀 더 명확하게 전달하기 위해서
``HTML
<section>
    <h1>섹션의 제목</h1>
    <p>...</p>
</section>

<nav>
    <h1>메뉴</h1>
    <ul>
        <li>
            <a href="#">링크</a>
        </li>
    </ul>
</nav>
```

### section vs article
- article은 내용이 독립적
article 태그는 section과 다르게 독립적으로 존재할 수 있으며 재사용 할 수 있다. 주로 블로그글, 포럼, 뉴스 기사 등을 article로 묶음
즉, article이 좀 더 구체적


- section은 주제별로 구분한 그룹
논리적으로 관계있는 요소 또는 문서를 분리할 때 사용
다른 주제의 문서를 구분 짓기위해 사용 (주제별 영역들을 그룹화)


#### header
문서의 도입부 또는 어떤 섹션의 시작을 마크업할 때 사용
```HTML
<header></header>
```

#### main
본문에 있어서 가장 핵심이 되는 부분을 묶어줄 때 사용
**제약** : 하나의 HTML 파일에는 단 하나의 `main`태그만 사용 가능
```HTML
<main></main>
```

#### footer 
문서의 하단부를 마크업할 때 사용
```HTML
<footer></footer>
```

-> 그냥 `div` 사용하는 것보다 의미가 더 부곽이 되는 효과