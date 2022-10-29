# 미션 - 온보딩

## 🔍 진행 방식

- 미션은 **기능 요구 사항, 프로그래밍 요구 사항, 과제 진행 요구 사항** 세 가지로 구성되어 있다.
- 세 개의 요구 사항을 만족하기 위해 노력한다. 특히 기능을 구현하기 전에 기능 목록을 만들고, 기능 단위로 커밋 하는 방식으로 진행한다.
- 기능 요구 사항에 기재되지 않은 내용은 스스로 판단하여 구현한다.

## 📮 미션 제출 방법

- 미션 구현을 완료한 후 GitHub을 통해 제출해야 한다.
    - GitHub을 활용한 제출 방법은 [프리코스 과제 제출](https://github.com/woowacourse/woowacourse-docs/tree/master/precourse) 문서를 참고해
      제출한다.
- GitHub에 미션을 제출한 후 [우아한테크코스 지원](https://apply.techcourse.co.kr) 사이트에 접속하여 프리코스 과제를 제출한다.
    - 자세한 방법은 [제출 가이드](https://github.com/woowacourse/woowacourse-docs/tree/master/precourse#제출-가이드) 참고
    - **Pull Request만 보내고 지원 플랫폼에서 과제를 제출하지 않으면 최종 제출하지 않은 것으로 처리되니 주의한다.**

## 🚨 과제 제출 전 체크 리스트 - 0점 방지

- 기능 구현을 모두 정상적으로 했더라도 **요구 사항에 명시된 출력값 형식을 지키지 않을 경우 0점으로 처리**한다.
- 기능 구현을 완료한 뒤 아래 가이드에 따라 테스트를 실행했을 때 모든 테스트가 성공하는지 확인한다.
- **테스트가 실패할 경우 0점으로 처리**되므로, 반드시 확인 후 제출한다.

### 테스트 실행 가이드

- 터미널에서 `java -version`을 실행하여 Java 버전이 11인지 확인한다. 또는 Eclipse 또는 IntelliJ IDEA와 같은 IDE에서 Java 11로 실행되는지 확인한다.
- 터미널에서 Mac 또는 Linux 사용자의 경우 `./gradlew clean test` 명령을 실행하고,   
  Windows 사용자의 경우  `gradlew.bat clean test` 명령을 실행할 때 모든 테스트가 아래와 같이 통과하는지 확인한다.

```
BUILD SUCCESSFUL in 0s
```

---

## 🚀 기능 요구 사항
아래의 7가지 기능 요구 사항을 모두 해결해야 한다.

1. [문제 1](./docs/PROBLEM1.md)
  * 처리 요구사항   
    1. 포비가 이긴다면 1, 크롱이 이긴다면 2, 무승부 0, 예외사항 -1 
  * 예외처리 요구사항   
    1. 연속되지 않은 두 수가 리턴되면 예외처리   
    1. 왼쪽 페이지는 홀수, 오른쪽 페이지는 짝수가 아니면 예외처리   
    1. 매개변수 두 리스트의 길이가 각각 2인지 확인   

2. [문제 2](./docs/PROBLEM2.md)
  * 출력값 요구사항
      1. 주어진 문자열의 chipher text를 출력
3. [문제 3](./docs/PROBLEM3.md)
4. [문제 4](./docs/PROBLEM4.md)
5. [문제 5](./docs/PROBLEM5.md)
6. [문제 6](./docs/PROBLEM6.md)
7. [문제 7](./docs/PROBLEM7.md)

---

## 🎯 프로그래밍 요구 사항

- JDK 11 버전에서 실행 가능해야 한다. **JDK 11에서 정상적으로 동작하지 않을 경우 0점 처리한다.**
- `build.gradle`을 변경할 수 없고, 외부 라이브러리를 사용하지 않는다.
- 프로그램 종료 시 `System.exit()`를 호출하지 않는다.
- 프로그램 구현이 완료되면 `ApplicationTest`의 모든 테스트가 성공해야 한다. **테스트가 실패할 경우 0점 처리한다.**
- 프로그래밍 요구 사항에서 달리 명시하지 않는 한 파일, 패키지 이름을 수정하거나 이동하지 않는다.

---

## ✏️ 과제 진행 요구 사항

- 미션은 [java-onboarding](https://github.com/woowacourse-precourse/java-onboarding) 저장소를 Fork & Clone해 시작한다.
- 과제 진행 및 제출 방법은 [프리코스 과제 제출](https://github.com/woowacourse/woowacourse-docs/tree/master/precourse) 문서를 참고한다.


--- 
## 🍀 기능 목록

1. 문제1

|기능목록 번호| 내용 | 구현상황 |
| :---:  | :--- | :--- | 
|  1.0 | 주어진 게임의 결과를 도출 | Problem1.solution | 
|  1.0.0 | 출력값 요구사항1의 구현 : 포비가 이긴다면 1, 크롱이 이긴다면 2, 무승부 0, 예외사항 -1  | Problem1.solution | 
|  1.0.1 | 예외 요구사항1의 구현 : 연속되지 않은 두 수가 리턴되면 예외처리    | Problem1.solution | 
|  1.0.2 | 예외 요구사항2의 구현 : 왼쪽 페이지는 홀수, 오른쪽 페이지는 짝수가 아니면 예외처리    | Problem1.solution | 
|  1.0.3 | 예외 요구사항3의 구현 : 매개변수 두 리스트의 길이가 2인지 확인 | Problem1.solution | 
|  1.1 | 주어진 리스트 배열의 게임의 결과값을 반환 | Problem1.findGameValue | 
|  1.2 | 주어진 숫자의 자릿수들의 합 | Problem1.sumOfDigits | 
|  1.3 | 주어진 숫자의 자릿수들의 겁 | Problem1.productOfDigits| 

2. 문제2

|기능목록 번호| 내용 | 구현상황 |
| :---:  | :---: | :--- | 
|  2.0 | 주어진 텍스트의 최종 cipher text를 출력 | Problem2.solution  | 
|  2.1 | 주어진 텍스트를 1회 해독한 결과를 출력 | Problem2.decipher  | 
