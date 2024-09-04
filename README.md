# web-animations-API
![image](https://github.com/user-attachments/assets/e791df51-588a-4327-a2a5-a7207351933f)
<br>

라이브러리를 사용해야 가능했던 웹 애니메이션 관련 기능들의 표준 구현체이다.<br>
CSS 애니메이션 구현을 기반으로 설계된 API로,<br>기존 CSS 애니메이션의 장점을 살리면서 구현은 더 간편한 것이 특징이다.

<br>

## What I Learned
- 자바스크립트로 CSS 애니메이션을 자유자재로 컨트롤<br>
- 웹 애니메이션 표준 기술(Web Standard)

<br>

## Todo
- [x] [CSS animation VS JS animation](https://github.com/twilight92/web-animations-API/wiki/CSS-%EC%95%A0%EB%8B%88%EB%A9%94%EC%9D%B4%EC%85%98%EA%B3%BC-JS-%EC%95%A0%EB%8B%88%EB%A9%94%EC%9D%B4%EC%85%98) 알아보기
- [x] [CSS Transition](https://github.com/twilight92/web-animations-API/wiki/CSS-Transition%EA%B3%BC-CSS-Animation)
  - object 태그를 활용하여 svg에 transition 적용 실습
- [x] [CSS Animation](https://github.com/twilight92/web-animations-API/wiki/CSS-Transition%EA%B3%BC-CSS-Animation#css-animation)
- [x] GPU 가속과 레이아웃 재계산이 필요한 속성들 알아보기
- [x] [Web Animation API](https://github.com/twilight92/web-animations-API/wiki/Web-Animation-API) 기본
  - Web Animation API란?
  - 기본 애니메이션 만들기
  - 키프레임과 옵션 분리하기
  - 애니메이션 컨트롤(Promise 사용가능)
    - `animation.play()`
    - `animation.pause()`
    - `animation.playbackRate`
    - `animation.playState`
    - `animation.finished`
    - `animation.ready`
  - 애니메이션 생성자 이용
- [x] [여러 개의 객체에 애니메이션 적용하기](https://github.com/twilight92/web-animations-API/wiki/%EC%97%AC%EB%9F%AC-%EA%B0%9C%EC%9D%98-%EA%B0%9D%EC%B2%B4%EC%97%90-%EC%95%A0%EB%8B%88%EB%A9%94%EC%9D%B4%EC%85%98-%EC%A0%81%EC%9A%A9%ED%95%98%EA%B8%B0)
  - 각각의 객체에 개별 애니메이션 적용하기
  - GroupEffect로 한꺼번에 애니메이션 적용하기
  - SequenceEffect로 순차적으로 애니메이션 적용하기
  - Starfield 만들기
