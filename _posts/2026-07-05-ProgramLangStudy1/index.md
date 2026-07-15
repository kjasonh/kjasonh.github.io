---
title: 프로그래밍 언어 스터디 (1)
author: Jihwan Kim
date: 2026-07-15
category: Study
layout: post
series: programming languages
series_order: 1
---

이 포스트에서는, 프로그래밍 언어 이론의 대표적 인물들을 알아보고, Grammar를 만들기 위해 기초가 되는 지식들을 정리해보겠습니다.


## 프로그래밍 언어 이론의 대표적인 인물들

대표적으로 John Backus, Peter Naur, Noam Chomsky 세 명의 인물이 있음.

John Backus → FORTRAN, ALGOL에 기여.  
간단하고, powerful한 notation을 처음 만듬. 


Peter Naur → ALGOL 리포트 편집자.  
Backus의 notation을 사용하여 ALGOL의 문법을 모두 명시함으로 대중화 시킴. 

이 notation이 둘의 이름을 따서 Backus-Naur Form, BNF으로 불리게 되었고,
좀 더 간략화시킬 수 있는 확장된 버전인 Extended BNF를 EBNF라고 부름.

Noam Chomsky → 자연어의 문법적 구조를 명시하려고 시도.
언어의 복잡성에 따른 4가지 분류를 만듬. Chomsky Hierarchy. 춈스키 위계의 type이 0부터 3까지 있을 때, type 2가 BNF/EBNF와 동일한 수준의 힘을 가지고 있음. 

![image1](_posts/2026-07-05-ProgramLangStudy1/image.png)

formal language와 automata theory의 주제들 아래에서, 춈스키 위계에 속한 language들이 CS, mathematics, linguistics과 함께 연구되어 졌음.