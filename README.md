# toy-notion

## 네이밍 규칙
- id: UPPER_SNAKE_CASE
- class: kebab-case
- JS 변수·일반 함수: camelCase
- JS 클래스·컴포넌트·생성자 함수: PascalCase
---
* UPPER_SNAKE_CASE → SIDEBAR_PEEK_BTN
: 모든 문자를 대문자로 쓰고 단어를 언더스코어(`_`)로 구분한다.
JavaScript에서는 변하지 않는 상수 이름에 주로 사용한다.
현재 프로젝트에서는 JavaScript로 제어할 HTML 요소의 `id`에도 사용한다.
---
* kebab-case → sidebar-peek-btn
: 모든 문자를 소문자로 쓰고 단어를 하이픈(`-`)으로 구분한다.
CSS 클래스와 HTML 파일 이름에 많이 사용한다.
현재 프로젝트에서는 CSS 스타일을 적용할 `class` 이름에 사용한다.
---
* camelCase → sidebarPeekBtn
: 첫 단어는 소문자로 시작하고, 이후 단어의 첫 글자를 대문자로 작성한다.
JavaScript의 변수, 일반 함수, 객체의 속성 이름에 주로 사용한다.
---
* PascalCase → SidebarPeekBtn
: 모든 단어의 첫 글자를 대문자로 작성한다.
JavaScript의 클래스, 생성자 함수, React와 같은 환경의 컴포넌트 이름에 주로 사용한다.
---

## 커밋메시지 규칙


