---
title: "React의 render phase와 commit phase"
date: 2025-05-11
categories: [매일메일]
tags: [GitHub 블로그, React]
---

배운 내용:

* [React는 컴포넌트의 props나 state가 바뀌면, 바뀐 부분과 관련된 컴포넌트들을 실행해서 새로운 UI가 어떻게 생겨야 할지 가상으로 계산함]
* [Render Phase: UI를 어떻게 업데이트할지 결정하고 계획하는 단계]
* [Commit Phase: 계획된 대로 실제 화면(DOM)에 반영하고 부수적인 작업을 처리하는 단계]
* [React는 가상 DOM이라는 추상화 계층을 사용하여 효율적인 UI 업데이트를 관리하지만, C++ GUI 프레임워크는 각자의 방식으로 화면 업데이트를 처리함]
* [React의 Render Phase는 순서가 보장되지 않고 중단될 수 있는 특징이 있지만, C++ GUI 프로그래밍에서는 일반적으로 UI 업데이트 요청이 들어오면 순차적으로 처리되는 경향이 있음]

느낀점:
[계획을 하면 적용해야죠.]