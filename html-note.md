# [input type = 'button'] VS [button type = 'button']

+ button 태그는 HTML 4.0 이후에 나왔다고 한다.
+ 옛날 웹페이지에서 대부분의 상호작용은 input의 submit으로 해결했다.
+ 따라서 이제 input-type-button을 굳이 쓸 이유는 없다.

### button에 type을 또 button이라고 쓰는 이유
  
  + button의 type에는 총 3가지가 있다.
    - submit(default), reset, button
    - 타입 명시 없으면 submit되니까 button 쓰는거
  + IE10 이하에서, form에 속하지 않은 input에 엔터를 치면, 애꿎은 button이 실행된다. 
    - button의 타입 명시를 해주면 이런 일이 예방된다.
  
### 두개 차이 또 하나

  + input태그는 열린태그라 자식요소를 가질 수 없다.
  + button태그는 닫힌태그라 자식요소를 가질 수 있다. -> input type="button"으로는 못하는 일들을 해줄 수 있음

참고:https://nykim.work/96
