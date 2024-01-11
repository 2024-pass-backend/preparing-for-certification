## 클린코드 작성원칙
- 가독성 : 이해하기 쉬운 용어를 사용한다.
- 단순성 : 한번에 한 가지 처리만 수행한다.
- 의존성 : 코드의 변경이 다른 부분에 영향이 없게 작성한다.
  - 의존성을 낮추고, 독립성을 높여야함.
  - 응집도를 높이고, 결합도를 낮춰야함.
  - **높여야하는 건 독립성, 응집도**
- 중복성 : 중복된 코드를 제거하고, 공통된 코드를 사용한다.
- 추상화 : 상세 내용은 하위클래스에서 구현한다.

## 테스트 단계
- 단위테스트 > 통합테스트 > 시스템 테스트 > 인수테스트

- 단위테스트 : 개발자가 하는 것으로, 동적분석과 정적분석으로 나뉜다.
  - 정적은 소스코드 실행시키지 않은 상태에서 소스코드 내부를 보는 것
  - 동적은 입력값을 넣고 출력값을 확인하는 것

- 통합테스트
  - 상향식 : 테스트드라이버
  - 하향식 : 테스트 스텁
  - 빅뱅 : 다 만드는것(비점진적 테스트)
  - 벡본 : 상향식 + 하향식 / 테스트드라이이버 + 테스트 스텁 둘다 사용

- 시스템 테스트
  - 기능 테스트 / 비기능 테스트

- 인수테스트
  - **알파테스트(완전중요)** : 사용자와 개발자 함께
  - 베타테스트 : 개발자 빠진 상태에서

## 스택(Stack)
- LIFO(Last-In-First-Out)

## Deque
- 선형리스트의 양쪽 끝에서 삽입과 삭제가 모두 가능한 자료구조
- 종류
  - 입력 제한 데크(Scroll) : 입력이 한쪽 끝으로 제한
  - 출력 제한 데크(Shelf) : 출력이 한쪽 끝으로 제한

## 자료구조 분류
자료구조 
- 선형 구조
  - 리스트
    - 선형 리스트(배열)
    - 연결 리스트(하나의 노드에 다음 노드의 포인터가 들어감)
  - 스택 : 깊이 우선에 사용
  - 큐 : 너비 우선에 사용
  - 덱
    - 입력제한데크(Scroll)
    - 출력제한데크(Shelf)
- 비선형 구조
  - 트리
  - 그래프

## 소프트웨어 프로젝트 관리(=목적)
- 주어진 기간 내에 최소의 비용으로 사용자를 만족시키는 시스템을 개발

## 정형기술검토(FTR) (잘 안나옴)
- 정형기술검토는 인스펙션의 한종류임!
- 지침
  - 의제를 제한한다.
  - 논쟁과 반박을 제한한다.
  - 문제 영역을 명혹히 표현한다.
  - **제기된 모든 문제를 바로 해결하지 않음!**

## 요구사항 검증방법(소스코드 품질분석)
- 동료검토(=개발자 검토)
    - 2 ~ 3명이 진행하는 리뷰형태로, **작성자가 명세서를 설명하고 이해관계자(동료)들이 들으면서 결함을 발견하는 형태**
- 워크스루
    - 검토자료(=요구사항명세서)를 **회의전에 배포하여 사전 검토한후,**
    - **짧은 시간동안 회의를 진행하는 형태**로, **오류를 조기에 검출**하는데 목적을 둔 검증기법
- 인스펙션
    - 공식적 검사회의
    - **명세서 작성자를 제외한** 다른 검토 전문가들이 확인하면서 결함을 발견하는 형태

- 동료검토, 워크스루, 인스펙션 같은 것을 실행한 후 리팩토링을 하게 된다!

## 소프트웨어 3할
- 재공학
- 역공학
- 재사용

- 재개발은 해당되지 않음!

## Migration
- 소프트웨어 재공학의 주요 활동 중 기존 소프트웨어 시스템을 새로운 기술 또는 하드웨어 환경에서 사용할 수 있도록 **변환하는 작업**

## 정보시스템 개발 단게에서 프로그래밍 언어 선택시 고려해야할 사항
- 개발 정보시스템의 특성
- 사용자의 요구사항
- 컴파일러의 가용성

## 소프트웨어 패키징
- 대표적인 예) **릴리즈 노트**
- 모듈로 생성한 실행 파일들을 묶어 배포용 설치 파일을 만드는 것
- **사용자 중심으로 진행한다.**
- 신규 및 변경 개발소스를 식별하고 이를 모듈화하여 상용제품으로 패키징한다.
- 고객의 편의성을 위해 메뉴얼 및 버전관리를 지속적으로 한다.
- 범용환경에서 사용이 가능하도록 일반적인 배포 형태로 패키징이 진행된다.

## SW패키징 도구 활용 시 고려사항
1) 반드시 암호화/보안을 고려한다.
2) 추가로 다양한 이기종 연동을 고려한다.
3) 사용자 편의성을 위한 복잡성 및 비효율성 문제를 고려한다.
4) 애플리케이션 종류에 적합한 암호화알고리즘을 적용한다.
5) 지속적인 배포를 고려한다.
