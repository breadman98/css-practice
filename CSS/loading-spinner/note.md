`스피너1`

키프레임 로테이션 0도,360도 해주면 됨 근데 html로 스피너 클래스를 하나 만들어준거를 css에서 flex하고 축 둘다 센터 -> 그래야 가운데서 빙글빙글 돌게됨 처음에 그냥 아이콘이니까 텍스트얼라인센터로 했는데 그러니까 축이 가운데로 딱 안잡혀서 도는게 이상했음

`스피너2`

display:flex;
flex-wrap:wrap; 으로 해서 요소배치를 이쁘게 해준다.
그다음 nth-child얘로 요소 하나하나 꾸며줌
border-radius:좌상,우상,우하,좌하; 순서임

    @keyframe 아이템{
      0% ~ 50% ~ 100% 이거를 그냥 한번에 50% 만 쓰는거랑 똑같다.
    }
