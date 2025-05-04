---
title: "React의 Controlled Component와 Uncontrolled Component"
date: 2025-04-30
categories: [매일메일]
tags: [GitHub 블로그, React]
---

배운 내용:

* [Controlled Component:
폼 요소의 현재 값은 React 컴포넌트의 state에 저장됨
사용자가 입력 요소의 값을 변경하면 (onChange 이벤트 발생), React는 이 이벤트를 감지하고 setState()를 사용하여 state 값을 업데이트
state 값이 업데이트되면 React는 해당 컴포넌트를 다시 렌더링하면서 폼 요소의 value 속성을 업데이트된 state 값으로 설정]
* [Uncontrolled Component:
폼 요소의 값은 일반적인 HTML 폼 요소처럼 DOM에 직접 저장됨
React는 입력 값이 변경되는 것을 직접적으로 알지 못함
폼 요소의 값을 얻으려면 useRef() 훅을 사용하여 DOM 요소에 직접 접근해야 함]
* [React의 Controlled Component는 state와 UI 요소의 value 속성을 양방향으로 바인딩하여 데이터 흐름을 명확하게 관리하는 특징이 있음]

느낀점:
[이해가 안 됐어요.]