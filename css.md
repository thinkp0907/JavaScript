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


