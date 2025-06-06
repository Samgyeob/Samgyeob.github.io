---
title: "React에서 성능 최적화를 위해 적용할 수 있는 방법"
date: 2025-05-01
categories: [매일메일]
tags: [GitHub 블로그, React]
---

배운 내용:

* [memo 사용 (똑같은 부품은 다시 그리지 않기)]
* [useCallback과 useMemo 사용 (함수와 값 재활용)]
* [코드 스플리팅 (React.lazy와 Suspense): 필요한 코드만 불러오기
뜻: 애플리케이션의 코드를 여러 개의 작은 덩어리(청크)로 나누고, 특정 시점에 필요한 코드만 동적으로 로딩하는 방식]
* [React의 최적화 방법과 유사한 아이디어를 C++에서도 찾아볼 수 있다.
Memoization: C++에서도 이미 계산된 결과를 저장해두고 동일한 입력이 들어왔을 때 다시 계산하지 않고 저장된 값을 반환하는 memoization 기법을 사용하여 성능을 향상시킬 수 있다. 특히 반복적인 계산이 많은 알고리즘에서 유용하다.

Lazy Initialization: C++에서도 객체나 변수를 실제로 사용될 때까지 초기화를 늦추는 lazy initialization을 통해 초기 로딩 시간을 줄이고 불필요한 연산을 피할 수 있다.

Code Splitting (동적 로딩): C++에서는 동적 라이브러리(.dll, .so)를 사용하여 프로그램 실행 중에 필요한 기능만 로딩하는 방식으로 애플리케이션의 초기 로딩 시간을 줄이고 메모리 사용량을 최적화할 수 있다.]

느낀점:
[이해가 안 됐어요.]