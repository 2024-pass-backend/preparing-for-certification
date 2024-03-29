## 미들웨어 개념 및 종류
- 미들웨어 : **클라이언트와 서버 간의 통신**을 담당하는 **시스템 소프트웨어**

- RPC : 원격 프로시저를 로컬 프로시저처럼 호출
- ORB : 코바 표준 스펙을 구현한 미들웨어
- TP monitor : 트랜잭션, 데이터 감시
- WAS : 동적인 콘텐츠를 처리
- MOM : 비동기형 메시지 전달
- DB : 데이터베이스와 연결

## UI 설계원칙(완전 중요, 실기에서 아예 쓰라고도 나옴)
- 직관성 : **누구나 쉽게 이해하고, 쉽게 사용**할 수 있어야함.
- 유효성 : **정확하고 완벽하게** 사용자의 목표, 목적이 달성될 수 있도록 제작
- 학습성 : **초보와 숙련자 모두가 쉽게 배우고 사용**할 수 있게 제작
- 유연성
  - **사용자의 인터렉션을 최대한 포용하고, 실수를 방지**할 수 있도록 제작
  - 사용자의 요구사항을 최대한 수용하며, **오류를 최소화**하여야함.

## XP(eXtreme Programing)의 5가지 가치
- XP : 수시로 발생하는 고객의 요구사항에 유연하게 대응하기 위해 고객의 참여와 개발과정의 반복을 극대화하여 개발 생산성을 향상시키는 방법

- 의사소통(Communication)
- 단순성(Simplicity)
- 용기(Courage)
- 피드백(Feedback)
- 존중(Respect)

## UML모델(완전 중요, 시험직전 암기)

- 구조적 다이어그램
  - 클래스 다이어그램
  - 객체 다이어그램
  - 컴포넌트 다이어그램
  - 배치 다이어그램
  - 복합체 구조 다이어그램
  - 패키지 다이어그램
  - 컴포지트 구조 다이어그램
  - 배포 다이어그램

- 행위 다이어그램
  - **유스케이스 다이어그램**
  - 시퀀스 다이어그램
  - 커뮤니케이션 다이어그램
  - 상태 다이어그램
  - 활동 다이어그램
  - 상호작용 개요 다이어그램
  - 타이밍 다이어그램

## 소프트웨어 개발 방법 중 요구사항 분석에 해당되는 것
- 요구사항 분석 기법 : 요구사항 중 명확하지 않거나 모호한 부분을 걸러내기 위한 방법

- 요구사항분류
- 개념모델링
- 요구사항할당
- 요구사항협상
- 정형분석

## 럼바우의 객체지향 분석절차(완전 중요)
- 객체모형 -> 동적 모형 -> 기능모형 (객 - 동 - 기)

## 공통 모듈 명세 기법의 종류
- 정확성 : 시스템 구현 시 해당 기능이 필요하다는 것을 알 수 있도록 정확히 작성
- 명확성 : 해당 기능을 이해할때 중의적으로 해석되지 않고 한가지로 해석될 수 있도록 작성
- 완전성 : 시스템 구현을 위해 필요한 모든 것을 기술
- 일관성 : 공통 기능들 간 상호 충돌이 발생하지 않도록 작성
- 추적성 : 기능에 대한 요구사항의 출처, 관련 시스템 등의 관계를 파악할 수 있도록 작성

## 객체지향 기법에서 사용되는 용어
- 집단화 : **클래스들 사이의 '부분-전체'관계 도는 '부분'의 관계로 설명됨**
- 일반화 : 공통적인 성질들을 상위클래스로 정의, 특수화된 객체들은 하위 부분형 객체로 정의(상속받아 사용)
- 추상화 : 복잡한 문제에 대해 불필요한 부분은 제거하고 핵심적인 부분만 초점을 두고 간략하게 만듬.(구체화)
- 캡슐화 : 객체의 행위오 자료를 하나로 묶고 구현 내용을 외부로부터 감추는 것(정보은닉)

## CASE(Compute-Aided-Software-Engineering)의 주요기능
- 그래픽 지원
- 소프트웨어 생명주기 전반적인 단계
- 다양한 소프트웨어 개발 모형을 지원

- 언어번역은 컴파일러나 인터프리터가 담당!

## DBMS 분석 시 고려해야할 사항
- 가용성
- 성능
- 기술지원
- 상호호환성
- 구축비용

## HIPO(Hierarchy Input Process Output)
- **하향식** 소프트웨어 개발을 위한 문서화도구 (**상향식은 UML**)
- 가시적 도표, 총체적 도표, 세부적 도표가 있음.
- 기능과 자료의 의존관계를 동시에 표현가능
- 시스템 실행과정인 입력/처리/출력의 기능을 표현
- 기호, 도표 등을 사용하므로, 보기 쉽고 이해하기도 쉬움
- HIPO Chart : 시스템의 기능을 여러 모듈을 고유모듈로 분할하여 이들간의 인터페이스를 계층구조로 표현한것

## Coad와 Yourdon방법
- 객체지향 분석 방법론 중 **E-R다이어그램**을 사용한 것

## Booch방법 
- 미시적, 거시적

## Jacobson방법
- UseCase

## Wirfs-Brocks방법
- 분석과 설계의 구분이 없다.
