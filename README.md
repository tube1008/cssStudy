CSS 선택자 작성법

* 선택자 {속성:값;}

- 선택자 : CSS 언어로 디자인하는 대상 ex) 태그, 클래스, 아이디 등
- {} 중괄호 : 속성과 값을 묶어주는 선택자의 속성 묶음 표시
- 속성 : 선택자에 적용하는 속성
- 값 : 속성에 해당하는 값
- ; 세미콜론 : 앞(좌측) 속성값이 여기서 종료했다는 것을 의미함

-CSS 색상 속성-
color : 글자 색상
background-color : 배경색상

# CSS style Sheet
-----------------------------------
## CSS 작성위치
* 내부스타일시트 `<head><style>여기 작성</style></head>`
* 외부스타일시트 styles/파일명.css 별도 생성 후
    `<link rel="stylesheet" href="./styles/파일명.css">`

-----------------------------------
## font-family 글꼴 설정
* `선택자 {font-family:'대표글꼴','보조글꼴'}`
* 모든 사용자에게 동일한 글꼴을 보여줄 수 있도록 웹 글꼴을 사용하는 것이 좋다!font.google.com