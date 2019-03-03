# fe_edu_imgslider

### 교육 목표
이미지 슬라이더를 이용해서 단계별로 리팩토링을 거쳐 MVC + Observer를 익힌다.

### 교육 자료
https://oss.navercorp.com/hunyong-song/fe_edu_imgslider/tree/master

### 교육 단계
1. Native ES5로 function - prototype을 사용하지 않고 `일반 함수`로만 개발
    - prev/next 버튼 클릭시 infinite이 되도록 구현
    - 3초 간격으로 auto slide가 되도록 구현
2. `생성자 함수 1개 - prototype 1개`로 리팩토링
3. 기능 단위로 분리해서 생성자 함수 3개 - prototype 3개(`MVC`)로 리팩토링
4. Model과 View를 `더 작은 단위로 분리 및 상속`을 사용해서 리팩토링
5. 모듈간의 의존성 문제가 생기면 `콜백 함수`를 사용해서 리팩토링
6. 옵저버 패턴을 적용해서 콜백 함수 대신 `옵저버 모듈을 상속`해서 리팩토링
7. jquery를 사용해서 `객체 간의 custom event`를 발생하도록 리팩토링
8. ES6를 사용해서 문법 리팩토링
9. jquery custom event 대신 `EventEmitter` 모듈 사용
