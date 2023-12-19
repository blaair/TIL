# Today I Learned

* **백행불여일기百行不如一記** : 보고 느끼고 행한 것들을 스스로 곱씹어 정제된 기록으로 남기자 !
* 



## 분류

### React.js

* [Next.js](React/nextjs.md)
* \[C2C 커머스 어플리케이션 개발] (Next.js, TypeScript)

### JavaScript

* [JavaScript](./)

### Algorithm

입출력 문제

* [231102 / 백준 / 2588 - 곱셈](Algorithm/231102-백준-2588.md)

조건문 문제

* [231102 / 백준 / 2884 - 알람 시계](Algorithm/231102-백준-2884.md)

### 퍼블

#### last-child가 작동하지 않을 때
- 원인 : 마지막 자식 아래에 또다른 요소가 존재한다면 last-child는 사용할 수 없다.
- 해결 : nth-last-of-type(1) 

#### 인라인 요소 가운데 정렬 (a 태그 등)
- 블록 요소라면 그냥 margin: auto만 주면 되지만, 인라인 요소이기에 display: block을 준다.
- display: block 을 주면 기본적으로 width 값이 100%로 바껴서 width 값을 정해준다.

- 만약 텍스트 길이에 따라 width 값을 조정해주어야 하는 번거로움이 있다면,
  - width: min-content;
  - white-space: nowrap; 
