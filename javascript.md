## JavaScript
- 기본적으로 JavaScript는 HTML 위에서 작용한다.
- Web Browser에게 JavaScript라는 것을 인식 시키기 위해서는 `<scipt></scipt>` 태그를 사용

>**ex)**  
>```html
><h1>JavaScript</h1>
><script>
>  document.write(1+1);
></script>
><h1>html</h1>
>1+1
>```

#### event
- onclick, onchange, onkeydown 등을 `Event`라고 부름

#### 선택자
- id선택자 > class 선택자 > 태그 선택자 

    | 값 | 사용하는 표현 |
    |---|:---:|
    | `class` | `.class`|
    | `tag` | `tag`|
    | `id` | `#id`|


- id와 class 의 차이
    - `class` = grouping / 포괄적
    - `id` = 한가지 대상을 식별 / 정확한 타게팅, 그룹내 예외

### JavaScript로 선택하기

- JavaScript에서 select tag by css selector
    > element = document.querySelector('Selector')
- JavaScript element style
    > x = document.querySelector('Selector').style
- JavaScript style background-color
    > document.body.style.backgroundColor = "red";


### 조건문
- JavaScript에서 조건문을 쓸때 비교연산자로 `===` 를 쓴다


### 리펙토링 Refactoring
> - 코딩을 하고나면 코드가 비효율적인 면이 생긴다. 그러면 동작 부분은 그대로 두고 코드 자체를 아주 효율적으로 만들어서 코드 가독성을 높히고 유지보수하기 편리하게 만들고, 중복 코드를 낮추는 방향으로 다시 개선하는 작업을 Refactoring 이라고 한다.






## CSS

-  `<div>` 무색 무취에 태그 -> 화면 전체를 쓰기때문에 줄바꿈을 함
> **ex)**  
>```html 
> <div>Javascript</div> 
>```
> 

- `<span>` 무색 무취에 태그 -> 전체를 쓰지 않기때문에 줄바꿈을 안함
> **ex)**  
>```html
> <span>Javascript</span>
>```

- `<style>`tag는 마치 `<script>` tag 처럼 web에게 **`<script>`** tag 안에 것 들이 *`css`* 다 라고 말해주는 구분자이다.


