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
커밋 메시지는 다음 형식으로 작성한다.

### 타입

- feat (feature: 기능)
  새로운 기능을 추가할 때 사용한다.
  예: feat: 사이드바 접기 기능 구현

- fix (fix: 고치다, 수정하다)
   잘못된 동작이나 오류를 고칠 때 사용한다.
  예: fix: 문서 제목이 저장되지 않는 오류 수정

- docs (documentation: 문서화, 문서 자료)
  README, 사용 설명서, 학습 정리 등 문서를 작성하거나 수정할 때 사용한다.
  예: docs: HTML Head 학습 내용 정리

- style (style: 형식, 작성 방식)
  코드의 동작을 바꾸지 않고 들여쓰기·공백 등 작성 형식을 정리할 때 사용한다.
  CSS 디자인 변경을 의미하는 타입은 아니다.
  예: style: HTML 들여쓰기 통일

- refactor (refactor: 코드를 재구성하다)
  기존 기능을 유지하면서 코드 구조를 개선할 때 사용한다.
  예: refactor: 문서 저장 로직을 별도 파일로 분리

- test (test: 시험, 검사)
  동작을 검증하는 테스트 코드를 추가하거나 수정할 때 사용한다.
  예: test: 문서 삭제와 복원 테스트 추가

- chore (chore: 허드렛일, 일상적인 잡무)
  프로젝트 운영에 필요한 주변 관리 작업을 뜻한다.
  초기 폴더 설정, 개발 도구 설정처럼 앱의 기능 자체를 추가하지 않는 작업에 사용한다.
  예: chore: 프로젝트 폴더 구조 초기 설정

