# Acorn-Academy
## 훈련과정명 : 웹 서비스 기반 빅데이터 분석 및 개발자 양성과정
* 2022.06.28 - 사전OT 및 사전평가 진행 / 담당 매니저 : 조은미 팀장(02-538-3747)
* 2022.06.30 - 첫 등원(제 3 강의장) /

-------------------------------------------------------------------------------------------------------------------------------------------
* 강의 진도 순서(사용 개발툴 : visual studio code
1. html, css, javascript(정보, 디자인. 동작언어)
2. oracle database
3. java
4. jsp
5. spring framework
6. vue
마지막 2주는 중간 프로젝트

-------------------------------------------------------------------------------------------------------------------------------------------
2022.06.30

<html, css, javascript>

- html은 markup 언어(꺽쇄를 열고 닫는 것)
- element를 닫을때 / 사용안하면 중간에 넣을 요소가 없다는 뜻으로 해석(즉 단독으로 존재한다는 의미임.)
- 비주얼 코드 내에서 browser 열고 싶으면 alt+b 단축키
- h1 => h1(headline)이라는 element(요소)를 생성한다는 뜻
- headline은 최대 h6까지 생성 가능(단, 숫자가 늘어날때마다 폰트 크기는 점점 작아짐)


* 주석 : html - <!-- --> | css&javascript -  , /* */
- <!DOCTYPE html> => 이 문서는 html5 형식의 문서라고 웹브라우저에게 알리는 선언부
- html 문서는 head 요소와 body 요소로 구성된다.
- body 요소에는 주로 화면에 나타낼 요소를 작성한다.
- <script></script> => 여기에 작성한 javascript는 페이지 로딩시에 웹브라우저가 해석한다.


* alert 같이 개발자가 실행할 때 편하게 하도록 하기 위한 함수 : 빌트인 함수


- greet 라는 이름의 함수(기능) 만들기 -> 페이지 로딩시에 해석 x / 예약어 개념
로딩시에는 준비했다가 사용자가 특정 행위를 행했을 때 함수가 실행되도록 설정함!
콘솔에서 실행하여 함수를 표시할 수 있고 함수이름 + ()하면 실행됨.

- function은 함수 안에는 실행할 javascript를 작성할 수 있다.(미리 준비해 놓는 역할) (단, 함수를 로딩시에 실행시키면 작동을 하더라도 정상적인 작동이 아님.)

- xxx(attribute main/속성명)=""(attribute value/속성값) => attribute

-------------------------------------------------------------------------------------------------------------------------------------------

*  CSS에서 style을 지정해 줄때는 p, h1등은 그냥 바로 선언해주지만 id를 선언해줄때는 앞에 #이 붙어야함. (즉, 특정요소를 선택해서 선언해줄때는 #이 붙어야함.)

* id와 상관없이 그룹명으로 찾고 싶을 때는 앞에 .을 붙인다

* img 요소의 src 속성의 값으로는 로딩할 이미지가 위치한 경로를 적어놓으면 웹브라우저가 해당경로를 찾아서 이미지 데이터를 받아와서 화면상에 표시해 준다. alt 속성의 값으로는 이미지의 자세한 설명을 적으면 된다. img 요소는 인라인 요소이기 때문에 개행을 따로 해주지 않으면 한줄에 표기된다.
-> 쉽게 말해서 h1처럼 글자 입력 후 그림이 밑으로 내려오는 이유는 display에서 block으로 설정되어 있기 때문임. 단, 이미지는 이미지 출력에 필요한 공간만 확보되면 출력이 됨. 그림처럼 옆으로 한줄로 쌓이는 성격을 띔 => inline elemnet라고 함. 반대로 h1처럼 위에서 아래로 쌓이는 것은 block element라고 함.

*  id 속성은 특정 요소를 유일하게 식별하고자 할 때 사용하는 속성이다. 동일한 id 부여할 경우에는 markup 오류가 발생.
* class 속성은 특정 요소들을 같은 그룹으로 구성하고자 할 때 사용하는 속성이다.
* 선택자에서 띄어쓰기를 하면 자손 요소를 의미한다.

* span : 눈에 보이지 않지만 \n을 계속해서 해석해줌. 하지만 웹브라우저는 해석 x(스페이스바로 인식)

* b 요소는 단순히 굵은 글씨 / strong요소는 굵은 글씨 + 강조 의 의미도 가지고 있다.
* i요소는 단순히 이텔릭체 / em 요소는 이텍릭체 + 강조 의 의미도 가지고 있다
* inline 요소는 아무리 개입을 해도 한줄에 표기를 함

* ul : 순서 없는 목록(unordered list)
어떤 목록을 나타낼 때 문자열을 단순히 나열하는게 아니고 아래오 같이 구조화를 해서 나열해야 한다는 특징을 가지고 있음.
* ol : 순서 있는 목록(ordered list)
-> css영역에서 수정을 할 때 list-style-type는 목록 표시할 때 나타나는 숫자나 문양의 타입을 말하는 것임.


* dl : 정의형 목록(definition list)
-> dl 안에 dt & dd는 한 세트로 적용한다고 보면 됨. dd는 출력 시 왼쪽 마진만을 가지고 있는 것이 특징.

* table(표) 형식 정보를 출력하려고 할 시에는 약식과 정석이 존재.
* 약식
![image](https://user-images.githubusercontent.com/107795925/176635429-e25e40f9-7483-476a-a6bf-641898ff7be6.png)

* table 요소들을 사용한 정석
![image](https://user-images.githubusercontent.com/107795925/176635620-c3ef7644-a1fe-4cc1-a769-26f85909bb10.png)
            
* table border="" -> 표의 테두리선 굵기를 지정하는 것이다.
* 표의 제목은 caption에 명시해주면 됨.
* "<colgroup>" 은 column의 폭을 조절하는 함수로 내부에 width나 height를 설정해주면 됨.
* table의 자식 요소로는 thead, tbody, tfoot가 올 수 있다.

* tfoot : 최종으로 중요한 정보를 먼저 읽을 수 있도록 위로 올려주는 역할을 하는게 tfoot(tbody의 내용을 skip할 수 있음)
-> 시각적으로는 밑에 나오지만 body보다 먼저 읽어줌.

* column이나 row를 합칠 시에는 colspan OR rowspan 함수를 사용하면 됨.
![image](https://user-images.githubusercontent.com/107795925/176635714-9169cda4-7d10-481a-abe0-33309f15e98e.png)
            
            
            
-------------------------------------------------------------------------------------------------------------------------------------------
* 참고 사항

- 1em = 16px
- block-start = top
- block-end = bottom

- body와 div는 부모와 자식 관계 / body와 img는 자손관계(단, img는 div와 부모자식관계여야 성립이 됨

- display에서 block<-> inline 서로 상반되는 개념
