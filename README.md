## 공부한 내용 정리

### chapter1 (Bull's eyes)

- command + mouse left => { 를 쉽게 구분 가능
- alert action의 style

> 1. default : 위치 자유
> 2. cancel : 왼쪽으로 위치 고정

- general -> landscape left, right check => 시작시 가로로 시작
- 메소드 : 객체에 기능을 제공, 함수라고도 부른다
- 객체 : 메소드 + 데이터
- lroundf() => 가장 가까운 정수로 반올림하기
- 양수로 바꾸는 함수 abs or * -1 하기
- import Quartzcore => ani 효과

> CATransition 으로 느리게 변경 효과

---

### Basic Operators

- 튜플 => 왼쪽부터 비교가 들어간다 true 값 일때 까지

> ex) (1,2) < (1,3) => true    
> "a" < "b" true 알파벳 순서

- 삼항연산자 => 질문 ? 답1 (true) : 답2 (false)
- nil-coalescing 연산자 => a != nil ? a! : b (옵셔널 해제 느낌)

> a가 nil이 아닐때, 즉 값이 있으면 a를 쓰고 그렇지 않으면 b를 쓴다.  
> a ?? b (식 간결화)

- 범위 연산 => let range = ...5

> 1. range.contains(7) false
> 2. range.contains(4) true
> 3. range.contains(-1) true

- && => 둘다 true 일때만
- || => 둘중 하나만 true 일때만

### Strings and Characters



---

### 추가 내용

은닉화 : 함수 내에 지역 변수를 은닉화라고 생각하자
캡슐화 :  같은 역할을 하는 것들끼리 묶어놔서 사용하지만 그 세세한 내용 하나까지 알지 못하더라도 기능만 알고 쓰는 느낌

