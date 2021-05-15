- background-attachment

- header 태그 다음 section 태그

- 주석으로 태그 시작과 끝을 기록
<!-- section.main -->
<!-- //section.main -->

- 레이아웃 잡는 부분에서 그냥 position으로 처리함
  어떤 특별한? 효율성을 엄청나게 생각하는 것 같지는 않음

- css명에 대문자 들어가는 것 어떤가?

- 버튼을 a 테그로 작성함, 이것에 대해서는 의견이 분분한듯
  a 테그 / input type="button" / button

- aria-hidden ?

- letter-spacing 의 단위? 

- 가상선택자는 겹쳐 쓸 수 있다. 
  // .view:hover:after

- animation
  * animation을 주고자 하는 오브젝트에 animation-name 및 속성 설정
  * @keyframe 속성으로 name을 받아 엘리먼트 생성시작시점(0%)부터 생성완료(100%)까지 각 단계별 name의 속성을 정의함
  @keyframe name {
    0% {}
    n1% {}
    n2% {}
    ...
    n3% {}
    100% {}
  }
  https://poiemaweb.com/css3-animation