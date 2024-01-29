---
title: 코틀린으로 알고리즘 뿌시기
date: 2024-01-30 01:36:00 +09
categories: [BOJ]
tags: [
    kotlin,
    BOJ,
    백준,
    알고리즘,
    algorithm
    ]     # TAG names should always be lowercase
---

백준 온라인 강의 [알고리즘 기초1](https://code.plus/course/41) , [알고리즘 기초2](https://code.plus/course/42) 에 포함되어 있는 문제를 가져옴

<!-- <details>
<summary><b>공부하게 된 계기</b></summary>
<div markdown="1"> -->
## 공부하게 된 계기

학부 수업으로 모바일 프로그래밍을 들으며 코틀린 공부를 처음 했다. 교수님이 알려주신 대로 어찌저찌 자바처럼 코드를 짜왔는데, 
1. 이럴 거면 자바를 쓰지 코틀린으로 코딩하는 의미가 없음
2. 알고리즘을 제대로 공부한 적도 없어서 비효율적인 코드가 많이 나옴  
이런 이유로, 안드로이드 개발에 주로 쓰이는 코틀린으로 알고리즘을 공부해보려 한다.

- 현재 나의 수준  
     + 안드로이드 앱 만들면서 쓰던 함수만 쓰고 코틀린 특징인 간결한 문법, 상속을 제대로 처리하지 못함. destruction과 같은 용어 못 알아들음
  
- 관련 도서 검색 결과 
1. 이펙티브 코틀린: 유명해서 일단 샀는데 코딩 컨벤션, 클린 코드 관련 내용이라 내가 원하는 방향의 책에 안 맞는 것 같아서 나중에 꼭! 정독하기로 약속
2. 코틀린 인 액션 or 코틀린 공식 문서 정독 : 둘 중 뭘 선택해야 할지 고민이 많았는데, 안드방 고수분들께 여쭤본 결과 영어로 된 공식문서 보다 한국어가 더 이해하기 쉽다고 답변 받고 다른 책도 추천받았다.
3. 아토믹 코틀린 : 추천받음. 코틀린 액션과 목차를 비교해 봤는데, 기초에 빵꾸 뚫린 나에게 수준이 맞다고 생각하여 선택함. 백준 풀면서 적용하면서 정독해보자😅  


### 최종 계획

1. 아토믹 코틀린 부시고
2. 코틀린 인 액션 보고
3. 이펙티브 코틀린 보기

→ 세 가지 책 읽으면서 백준 **플레티넘**까지 코틀린으로 풀어보기!


<!-- 
</div>
</details> -->

## 자료구조

### 예제

- [ ] [스택](https://www.acmicpc.net/problem/10828)
- [ ] [단어 뒤집기](https://www.acmicpc.net/problem/9093)
- [ ] [괄호](https://www.acmicpc.net/problem/9012)
- [ ] [스택 수열](https://www.acmicpc.net/problem/1874)
- [ ] [에디터](https://www.acmicpc.net/problem/1406)
- [ ] [큐](https://www.acmicpc.net/problem/10845)
- [ ] [조세퍼스 문제](https://www.acmicpc.net/problem/1158)
- [ ] [덱](https://www.acmicpc.net/problem/10866)

### 연습

- [ ] [단어 뒤집기 2](https://www.acmicpc.net/problem/17413)
- [ ] [쇠막대기](https://www.acmicpc.net/problem/10799)
- [ ] [오큰수](https://www.acmicpc.net/problem/17298)
- [ ] [오등큰수](https://www.acmicpc.net/problem/17299)

### 참고

- [ ] [후위 표기식2](https://www.acmicpc.net/problem/1935)
- [ ] [후위 표기식](https://www.acmicpc.net/problem/1918)
- [ ] [알파벳 개수](https://www.acmicpc.net/problem/10808)
- [ ] [알파벳 찾기](https://www.acmicpc.net/problem/10809)
- [ ] [문자열 분석](https://www.acmicpc.net/problem/10820)
- [ ] [단어 길이 재기](https://www.acmicpc.net/problem/2743)
- [ ] [ROT13](https://www.acmicpc.net/problem/11655)
- [ ] [네 수](https://www.acmicpc.net/problem/10824)
- [ ] [접미사 배열](https://www.acmicpc.net/problem/11656)

## 수학

### 예제

- [ ] [나머지](https://www.acmicpc.net/problem/10430)
- [ ] [최대공약수와 최소공배수](https://www.acmicpc.net/problem/2609)
- [ ] [최소공배수](https://www.acmicpc.net/problem/1934)
- [ ] [소수 찾기](https://www.acmicpc.net/problem/1978)
- [ ] [소수 구하기](https://www.acmicpc.net/problem/1929)
- [ ] [골드바흐의 추측](https://www.acmicpc.net/problem/6588)
- [ ] [팩토리얼](https://www.acmicpc.net/problem/10872)
- [ ] [팩토리얼 0의 개수](https://www.acmicpc.net/problem/1676)
- [ ] [조합 0의 개수](https://www.acmicpc.net/problem/2004)

### 연습

- [ ] [GCD 합](https://www.acmicpc.net/problem/9613)
- [ ] [숨바꼭질 6](https://www.acmicpc.net/problem/17087)
- [ ] [2진수 8진수](https://www.acmicpc.net/problem/1373)
- [ ] [8진수 2진수](https://www.acmicpc.net/problem/1212)
- [ ] [-2진수](https://www.acmicpc.net/problem/2089)
- [ ] [골드바흐 파티션](https://www.acmicpc.net/problem/17103)

### 참고

- [ ] [진법 변환 2](https://www.acmicpc.net/problem/11005)
- [ ] [진법 변환](https://www.acmicpc.net/problem/2745)
- [ ] [Base Conversion](https://www.acmicpc.net/problem/11576)
- [ ] [소인수분해](https://www.acmicpc.net/problem/11653)

## 다이나믹 프로그래밍 DP

## 예제

- [ ] [1로 만들기](https://www.acmicpc.net/problem/1463)
- [ ] [2×n 타일링](https://www.acmicpc.net/problem/11726)
- [ ] [2×n 타일링 2](https://www.acmicpc.net/problem/11727)
- [ ] [1, 2, 3 더하기](https://www.acmicpc.net/problem/9095)
- [ ] [카드 구매하기](https://www.acmicpc.net/problem/11052)
- [ ] [카드 구매하기 2](https://www.acmicpc.net/problem/16194)
- [ ] [1, 2, 3 더하기 5](https://www.acmicpc.net/problem/15990)
- [ ] [쉬운 계단 수](https://www.acmicpc.net/problem/10844)
- [ ] [이친수](https://www.acmicpc.net/problem/2193)
- [ ] [가장 긴 증가하는 부분 수열](https://www.acmicpc.net/problem/11053)
- [ ] [가장 긴 증가하는 부분 수열 4](https://www.acmicpc.net/problem/14002)
- [ ] [연속합](https://www.acmicpc.net/problem/1912)
- [ ] [제곱수의 합](https://www.acmicpc.net/problem/2225)
- [ ] [합분해](https://www.acmicpc.net/problem/2225)

### 연습

- [ ] [1, 2, 3 더하기 3](https://www.acmicpc.net/problem/15988)
- [ ] [RGB거리](https://www.acmicpc.net/problem/1149)
- [ ] [동물원](https://www.acmicpc.net/problem/1309)
- [ ] [오르막 수](https://www.acmicpc.net/problem/11057)
- [ ] [스티커](https://www.acmicpc.net/problem/9465)
- [ ] [포도주 시식](https://www.acmicpc.net/problem/2156)
- [ ] [정수 삼각형](https://www.acmicpc.net/problem/1932)
- [ ] [가장 큰 증가 부분 수열](https://www.acmicpc.net/problem/11055)
- [ ] [가장 긴 감소하는 부분 수열](https://www.acmicpc.net/problem/11722)
- [ ] [가장 긴 바이토닉 부분 수열](https://www.acmicpc.net/problem/11054)
- [ ] [연속합 2](https://www.acmicpc.net/problem/13398)
- [ ] [타일 채우기](https://www.acmicpc.net/problem/2133)

### 도전

- [ ] [동물원](https://www.acmicpc.net/problem/1309)
- [ ] [RGB거리 2](https://www.acmicpc.net/problem/17404)
- [ ] [합분해](https://www.acmicpc.net/problem/2225)



## 브루트 포스

### 예제

- [ ] [일곱 난쟁이](https://www.acmicpc.net/problem/2309)
- [ ] [사탕 게임](https://www.acmicpc.net/problem/3085)
- [ ] [날짜 계산](https://www.acmicpc.net/problem/1476)
- [ ] [리모컨](https://www.acmicpc.net/problem/1107)
- [ ] [테트로미노](https://www.acmicpc.net/problem/14500)
- [ ] [카잉 달력](https://www.acmicpc.net/problem/6064)
- [ ] [수 이어 쓰기 1](https://www.acmicpc.net/problem/1748)
- [ ] [1, 2, 3 더하기](https://www.acmicpc.net/problem/9095)

### 브루트 포스 (N과 M)

- [ ] [N과 M (1)](https://www.acmicpc.net/problem/15649)
- [ ] [N과 M (2)](https://www.acmicpc.net/problem/15650)
- [ ] [N과 M (3)](https://www.acmicpc.net/problem/15651)
- [ ] [N과 M (4)](https://www.acmicpc.net/problem/15652)
- [ ] [N과 M (5)](https://www.acmicpc.net/problem/15654)
- [ ] [N과 M (6)](https://www.acmicpc.net/problem/15655)
- [ ] [N과 M (7)](https://www.acmicpc.net/problem/15656)
- [ ] [N과 M (8)](https://www.acmicpc.net/problem/15657)
- [ ] [N과 M (9)](https://www.acmicpc.net/problem/15663)
- [ ] [N과 M (10)](https://www.acmicpc.net/problem/15664)
- [ ] [N과 M (11)](https://www.acmicpc.net/problem/15665)
- [ ] [N과 M (12)](https://www.acmicpc.net/problem/15666)

### 브루트 포스 - 순열

- [ ] [다음 순열](https://www.acmicpc.net/problem/10972)
- [ ] [이전 순열](https://www.acmicpc.net/problem/10973)
- [ ] [모든 순열](https://www.acmicpc.net/problem/10974)
- [ ] [차이를 최대로](https://www.acmicpc.net/problem/10819)
- [ ] [외판원 순회 2](https://www.acmicpc.net/problem/10971)
- [ ] [로또](https://www.acmicpc.net/problem/6603)

### 브루트 포스 - 재귀

- [ ] [1, 2, 3 더하기](https://www.acmicpc.net/problem/9095)
- [ ] [암호 만들기](https://www.acmicpc.net/problem/1759)
- [ ] [퇴사](https://www.acmicpc.net/problem/14501)
- [ ] [스타트와 링크](https://www.acmicpc.net/problem/14889)
- [ ] [링크와 스타트](https://www.acmicpc.net/problem/15661)
- [ ] [부등호](https://www.acmicpc.net/problem/2529)
- [ ] [맞춰봐](https://www.acmicpc.net/problem/1248)

### 브루트 포스 - 비트마스크

- [ ] [집합](https://www.acmicpc.net/problem/11723)
- [ ] [부분수열의 합](https://www.acmicpc.net/problem/1182)
- [ ] [스타트와 링크](https://www.acmicpc.net/problem/14889)
- [ ] [종이 조각](https://www.acmicpc.net/problem/14391)

## 그래프

### 예제

- [ ] [ABCDE](https://www.acmicpc.net/problem/13023)
- [ ] [DFS와 BFS](https://www.acmicpc.net/problem/1260)
- [ ] [연결 요소의 개수](https://www.acmicpc.net/problem/11724)
- [ ] [이분 그래프](https://www.acmicpc.net/problem/1707)
- [ ] [단지번호붙이기](https://www.acmicpc.net/problem/4963)
- [ ] [섬의 개수](https://www.acmicpc.net/problem/2178)
- [ ] [미로 탐색](https://www.acmicpc.net/problem/7576)
- [ ] [토마토](https://www.acmicpc.net/problem/7562)
- [ ] [나이트의 이동](https://www.acmicpc.net/problem/7562)

### 연습

- [ ] [Two Dots](https://www.acmicpc.net/problem/16929)
- [ ] [서울 지하철 2호선](https://www.acmicpc.net/problem/16947)

### 도전

- [ ] [BFS 스페셜 저지](https://www.acmicpc.net/problem/16940)
- [ ] [DFS 스페셜 저지](https://www.acmicpc.net/problem/16964)
- [ ] [다리 만들기](https://www.acmicpc.net/problem/2146)

## BFS

- [ ] [숨바꼭질](https://www.acmicpc.net/problem/1697)
- [ ] [숨바꼭질 4](https://www.acmicpc.net/problem/13913)
- [ ] [이모티콘](https://www.acmicpc.net/problem/14226)
- [ ] [숨바꼭질 3](https://www.acmicpc.net/problem/13549)
- [ ] [알고스팟](https://www.acmicpc.net/problem/1261)

## 트리

- [ ] [트리 순회](https://www.acmicpc.net/problem/1991)
- [ ] [트리의 높이와 너비](https://www.acmicpc.net/problem/2250)
- [ ] [트리의 부모 찾기](https://www.acmicpc.net/problem/11725)
- [ ] [트리의 지름](https://www.acmicpc.net/problem/1167)
- [ ] [트리의 지름](https://www.acmicpc.net/problem/1967)