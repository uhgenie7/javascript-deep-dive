# 3. 자바스크립트 개발 환경과 실행 방법

## 3.1 자바스크립트 실행 환경

- 브라우저

  - HTML, CSS, JS를 실행해 웹 페이지를 브라우저 화면에 렌더링하는 것이 주된 목적
  - WEB API 사용가능

- Node.js

  - 브라우저 외부에서 자바스크립트 실행환경을 제공하는 것이 주된 목적
  - 파일을 생성하고 수정하는 파일 시스템을 제공

- WEB API(브라우저 환경)
  - DOM, BOM, Canvas, XMLHttpRequest, fetch, requestAnimationFrame, SVG, Web Storage, Web Component, Web Worker 등
    - [BOM(Browser Object Model)](https://wickies.tistory.com/26)
      - 웹 브라우저와 관련된 객체의 집합
      - 객체 모델 종류 : window, location, navigator, history, screen, document
      - DOM(Document Object Model)으로 통합해서 칭하기도 함

## 3.2 웹 브라우저

- 개발자 도구
  - 브라우저가 제공하는 개발자 도구(cmd + option + i)
- 콘솔
  - 에러 발생 시 에러메세지를 보여줌
  - 자바스크립트 코드를 직접 입력해 그 결과를 확인할 수도 있음
- 브라우저에서 자바스크립트 실행

  - HTML파일을 로드하면 script태그에 포함된 자바스크립트 코드를 실행
  - 예제 3-1
    - HTMLElement를 변수에 담는데 없다면 null
    - HTMLElement를 변수를 지을 때 $를 앞에 붙임

## 3.3 Node.js

### Node.js와 npm 소개

- npm(node package manager) : 자바스크립트 패키지 매니저
  - Node.js에서 사용할 수 있는 모듈들을 패키지화해서 모아둔 저장소 역할 +
  - 패키지 설치 및 관리를 위한 CLI(Command Line Interface)를 제공

### Node.js 설치

### Node.js REPL

- 터미널에서 node입력 시 브라우저 콘솔창 처럼 자바스크립트 코드를 실행해 결과를 확인해볼 수 있음
- node [자바스크립트 파일명] : 파일명의 자바스크립트 실행
