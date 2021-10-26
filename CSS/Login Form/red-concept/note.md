 `#1` form 태그의 action 속성

     정의 및 특징
     <form> 태그의 action 속성은 폼 데이터(form data)를 서버로 보낼 때 해당 데이터가 도착할 URL을 명시.

     문법
     <form action="URL">

     1. 절대 주소(absolute URL)
     ex) href=“http://www.tcpschool.com/target.php”

     2. 상대 주소(relative URL)
     ex) href=“target.php”


`#2` 그리드<br>
https://heropy.blog/2019/08/17/css-grid/<br>
flex가 편하긴한데 그리드도 알아놔야겠음

`#3` 선택자<br>

valid,invalid 가상선택자<br>
  >valid : 유효값 갖는 요소 <br>
  >invalid : 유효하지 않는 값 요소<br>

~선택자<br>
  >ex) h1 ~ p : h1뒤에 오는 형제 중 모든p.<br>
  >ex) h1 + p : h1 바로 뒤에 오는 형제요소p만.<br>


and,or 조건<br>
  >and : 선택자 사이에 공백없이 붙여서 사용 -> 여러 선택자를 동시에 만족할 경우<br>
  >or : 선택자 사이에 콤마를 붙여서 사용 -> 여러 선택자 중 하나라도 만족할 경우 <br>

`#4` box-sizing : border-box;<br>
https://www.codingfactory.net/10630

`참고` : 유튜브 codingLab<br>
타이틀 밑줄은 ::after에다가 새로 그림을 그려준다. content를 공백으로 주고 width,height,bg로 그림그려줌, 이 때 포지션을 잘 고려하자.<br>
input 밑줄은 hover,valid 때 효과를 줄 것이니 underline속성을 사용해서 넣어주는게 아니라 아예 html에서 .underline클래스로
공간을 잡아주고 css에서 다뤄주니 편하다
