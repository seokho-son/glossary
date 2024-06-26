---
title: 추상화 (Abstraction)
status: Completed
category: 속성
tags: ["기본 개념", "", ""]
---

컴퓨팅 관점에서 추상화는 [서비스](/ko/service/)의
소비자(컴퓨터 프로그램이나 사람을 의미)에게서
세부 사항을 숨기는 것을 의미하는 표현으로,
시스템을 보다 쉽고 일반적인 개념(generic)으로 이해할 수 있게 돕는다.
노트북의 운영체제(OS)를 좋은 예시로 볼 수 있다.
운영체제는 추상화를 통해 컴퓨터가 동작하는 방식에 대한 세부 사항이 드러나지 않게 한다.
따라서 사용자는 CPU, 메모리, 그리고 프로그램이 처리되는 세부 방식에 대해서 인지할 필요가 없다.
사용자는 OS만 사용하면 되고 나머지 세부 사항은 OS가 처리한다.
이러한 모든 세부 사항은 OS의 "커튼(curtain)", 즉 추상화 뒤에 숨겨진다.

시스템은 일반적으로 여러 계층(layer)으로 나뉘어 추상화되어 있다.
이러한 형태는 개발을 매우 단순화시킨다.
프로그래밍할 때 개발자는 특정 추상화 계층에 호환되는 구성 요소를 빌드하면 되므로,
이질적일 수 있는 기저(underlying)의 다양한 세부 사항에 대해 걱정할 필요가 없다.
해당 추상화 계층에서 문제 없이 작동한다면, 그 내부에 무엇이 있든지 상관없이
시스템에서 구동될 수 있다.
