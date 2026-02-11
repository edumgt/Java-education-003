# Java Education 003

이 저장소는 **Java 기초 문법부터 객체지향, 예외 처리, 컬렉션, 문자열/배열 알고리즘**까지 폭넓게 연습할 수 있도록 구성된 학습용 예제 모음입니다.

## 1) 기술 스택
- **Language**: Java (Java SE)
- **Runtime/JDK**: JDK 8+ 권장 (일반적인 `javac`, `java` 기반 실행)
- **Build Tool**: 별도 빌드 도구(Maven/Gradle) 없이 단일 `.java` 파일 중심 학습 구조
- **주요 표준 라이브러리**:
  - `java.util` (ArrayList, LinkedList, HashMap, Queue, PriorityQueue, Vector, TreeSet 등)
  - `java.io` (BufferedReader, Flush, Serializable 관련 예제)
  - `java.time`/`java.util.Date` 계열 사용 예제
- **개발 환경**: CLI 또는 VS Code 등 Java 실행 가능한 IDE

## 2) 프로젝트 구조
```text
src/main/java/
  ├─ 기초 문법/제어문 예제
  ├─ 함수/메서드 예제
  ├─ 문자열/배열 문제 풀이
  ├─ OOP (상속, 다형성, 인터페이스, 추상화)
  ├─ 예외 처리
  ├─ 컬렉션 프레임워크
  └─ 기타 실습 파일
```

## 3) 학습 주제 요약

### A. Java 기초 문법 & 제어문
- 조건문/반복문/분기문: `SwitchCase`, `BreakStatement`, `FiveIntegers`
- 숫자/진법/기본 연산: `Hexadecimal`, `DivisionEx`, `TwoNumberFunction`
- 정적/가변 인자/기본 클래스 요소: `StaticExample`, `VarargsExample`, `ClassProperties`

### B. 함수와 메서드 연습
- 팩토리얼/피보나치/거듭제곱: `FunctionFindFactorial`, `FunctionFibonacciSeries`, `FunctionCalculatePower`
- 소수/짝홀 판별 함수: `FunctionCheckPrimeNo`, `FunctionCheckEvnOdd`
- 문자열 뒤집기 함수형 접근: `FunctionToReverseString`

### C. 문자열 & 배열 알고리즘
- 문자열 비교/아나그램/회문: `StringCompare`, `CompareTwoString`, `AnagramCheck`, `CheckPalindrome`
- 문자 빈도/중복 제거/치환: `CharFrequency`, `DuplicateCharacters`, `ReplaceWordString`, `RemoveDuplicate`
- 배열 복사/합계/정렬/탐색: `CopyArray`, `SumOfArray`, `SortArrayAsc`, `DescendingSort`, `LinerSearch`

### D. 객체지향 프로그래밍(OOP)
- 캡슐화/생성자/오버로딩: `EncapsulationDemo`, `ConstructorOverloading`, `DefaultParameterized`
- 상속/다형성/오버라이딩: `DeepInheritanceDemo`, `PolymorphismExample`, `MethodOverride`
- 인터페이스/추상 클래스: `InterfaceDemo`, `ImplementsInterface`, `AbstractClass`, `AbstractVsInterface`
- 설계 패턴 기초: `PaymentFactoryDemo` (Factory Pattern 실습)

### E. 예외 처리
- try-catch-finally 기본: `TryCatch`, `FinallyEx`, `ExceptionHandling`
- 다중 catch/중첩 처리: `MultipleCatch`, `NestedTryCatchEx`
- throw/throws 및 사용자 정의 예외: `ThrowEx`, `ThrowVsThrows`, `CustomCheckedEx`
- 대표 런타임 예외 케이스: `DivisionByZero`, `ArrayIndexOutOfBound`, `UncheckedException`

### F. 컬렉션 프레임워크
- List 계열: `ArrayListExample`, `LinkedListEx`, `VectorThreadSafety`
- Set/Map 계열: `UniqueIntegerSet`, `HashMapExample`, `MapMethod`, `HashMapEntrySet`
- Queue/우선순위 큐: `QueueExample`, `PriorityQueueExample`
- 컬렉션 특성 비교: `ListSetComparison`, `CollectionIntro`, `FailFastIterator`

### G. 입출력/기타 개념
- 입출력: `BufferedReaderUsage`, `FlushExample`, `SystemErr`
- 직렬화/키워드: `Transient`, `FinalKeyword`, `FinalDemo`, `ThisKeywordConstructor`
- 날짜/유틸: `DateExample`, `RegexExample`, `WrapperStream`

## 4) 실행 방법 (예제 1개씩 권장)
이 저장소는 동일 패키지 내 학습용 클래스가 많아, **파일 단위로 컴파일/실행**하는 방식이 가장 안정적입니다.

```bash
# 예시: ArrayListExample 실행
javac src/main/java/ArrayListExample.java
java src.main.java.ArrayListExample
```

> 참고: 전체 파일을 한 번에 컴파일하면 클래스명 충돌(동일 이름 클래스)로 오류가 날 수 있습니다.

## 5) 추천 학습 순서
1. **기초 문법/제어문**
2. **함수/메서드**
3. **문자열/배열 문제 풀이**
4. **OOP 핵심(상속/다형성/인터페이스/추상화)**
5. **예외 처리 + 컬렉션 심화**
6. 필요 시 설계 패턴(`PaymentFactoryDemo`)으로 확장

## 6) 이런 분께 추천
- Java 문법을 빠르게 훑고 싶은 입문자
- 코딩 테스트 기초(문자열/배열)와 OOP를 같이 연습하고 싶은 학습자
- 예외 처리/컬렉션 사용 감각을 예제로 익히고 싶은 개발자
