## 요구사항 확인
- 요구사항 분류
  - 기능적 요구사항 : 시스템이 제공하는 기능
  - 비기능적 요구사항 : 시스템 구축에 대한 제약사항에 관한 요구사항
    - 보안, 성능, 품질이 비기능적 요구사항에 해당된다.
- 요구공학 프로세스 순서(중요)
  - 도출
  - 분석
  - 명세서
  - 확인
  - 도, 분, 명, 확

## 데이터베이스 설계할때 사용하는 다이어그램
- ERD (Entity-Relationship Diagram)
  - entity는 네모로, 속성은 동그라미, 
  - 마름모는 주문.. 같은 것!

## UI설계지침(완전 중요, 2020년에 나옴!)
- 직관성 : **누구나 쉽게 이해하고, 쉽게 사용**할 수 있어야함.
- 유효성 : **정확하고 완벽하게** 사용자의 목표, 목적이 달성될 수 있도록 제작
- 학습성 : **초보와 숙련자 모두가 쉽게 배우고 사용**할 수 있게 제작
- 유연성
    - **사용자의 인터렉션을 최대한 포용하고, 실수를 방지**할 수 있도록 제작
    - 사용자의 요구사항을 최대한 수용하며, **오류를 최소화**하여야함.

- 이해하기 편하고 쉽게 사용할 수 있는 환경을 제공해야한다.
- 주요 기능을 메인 화면에 노출하여 조작이 쉽도록 해야한다.
  - 마치, 네이버에 새로운 메일이 왔다면, 바로 확인이 가능한 상황을 말함!
- 사용자의 직무, 연령, 성별 등 다양한 계층을 수용해야한다.

## 객체지향 개념 중 다형성
- 다형성 종류
  - 오버로딩 : 같은 형태로 여러개 만드는 것. (A(a), A(a,b) 처럼 파라미터만 다르게 하는 것, 형태는 같음)
  - 오버라이딩 : 상속관계에서 존재하는 것으로, 부모가 물려준 것을 재정의함.

- 다형성 개념
  - 다형성은 현재 코드를 변경하지 않고 새로운 클래스를 쉽게 추가할 수 있다.
  - 다형성이란 여러가지 형태를 가지고 있다는 의미로, 여러 형태를 받아들일 수 있는 특징을 말한다.
  - 메소드 오버라이딩은 상위클래스에서 정의한 일반 메소드의 구현을 하위클래스에서 무시하고 재정의할 수 있다.
  - 메소드 오버로딩은 매개변수는 다르게, 메소드명을 같게!

## 객체 지향 프로그래밍의 특징
- **추상화** : 다형성과 관련있음.
- **캡슐화** : 정보은닉과 관련있음, 외부에서 함부로 보지 못하게 하는것!
- **상속** : 부모에게 물려받는 것
- **다형성** : 오버로딩, 오버라이딩 
- 동적 바인딩 : 형태를 그때그때 바꿀 수 있음.

## 인터페이스 개념
- 기존의 소프트웨어와 새로운 소프트웨어를 **연결**하는 소프트웨어

## EAI(EAI 유형 완전중요)
- 기업에서 운영하는 서로 다른 플랫폼, app간의 정보 전달, 연계, 통합을 위한 솔루션을 말한다.
- 유형
  - Point to Point 
  - Hub&Spoke
  - Message Bus
  - Hybrid

## 객체
- 상태, 동작, 고유식별자를 가진 모든 것이라 할 수 있다.
- 필요한 자료구조와 이에 수행되는 함수들을 가진 하나의 독립된 존재이다.
- 객체의 상태는 속성값에 의해 정의된다.
- 객체 : 멤버변수 + 메소드

## Encapsulation
- 속성과 관련된 연산을 클래스 안에 **묶어서 하나로 취급**하는 것

## 애자일(Agile) 프로세스 모델
- 공정과 도구보다 **개인과 상호작용**
- 포괄적인 문서보다는 **작동하는 소프트웨어**
- 계약 협상보다는 **고객과의 협력을**
- 계획을 따르기보다는 **변화에 대응하기를**

## Component
- 명백한 역할을 가지고 **독립적으로 존재**할 수 있는 시스템의 부분으로 넓은 의미에서는 재사용되는 모든 단위라고 볼 수 있으며,
- 인터페이스를 통해서만 접근할 수 있다.

## GoF(Gang of Four)의 디자인 패턴(완전 중요, 시험직전에 암기, 2020년에도 나옴!)
- 생성패턴
    - 팩토리메소드(Factory Method)
    - 싱글톤(SingleTone)
    - 추상팩토리(Abstract Factory)
    - 빌더(Builder)
    - 프로토타입(Prototype)
- 구조패턴
    - 어댑터(Adapter)
    - 브릿지(Bridge)
    - 컴포지트(Composite)
    - 데코레이터(Decorator)
    - 퍼싸드(Facade)
    - 플라이웨이트(Fly weight)
    - 프록시(Proxy)
- 행위패턴
    - 템플릿메소드(Template Method)
    - 인터프리터(Interpreter)
    - 반복자(Iterator)
    - 커멘드(Command)
    - 책임연쇄(Chain of Responsibility)
    - 상태(State)
    - 전략(Strategy)
    - 중재자(Mediator)
    - 메멘토(Memento)
    - 방문자(Visitor)
    - 옵저버(Observer)

- 참조 블로그 : [디자인패턴](https://skyjava93.tistory.com/entry/%EC%A0%95%EB%B3%B4%EC%B2%98%EB%A6%AC%EA%B8%B0%EC%82%AC-%EC%8B%A4%EA%B8%B0-%EA%B0%9C%EB%85%90%EC%A0%95%EB%A6%AC-2-%EB%94%94%EC%9E%90%EC%9D%B8%ED%8C%A8%ED%84%B4)

## 디자인패턴의 구성
- 패턴이름 및 유형
- 문제 및 배경
- 해결방안
- 사례
- 결과
- 샘플코드

## Feedback
- UI와 관련된 기본 개념 중 하나로, 시스템의 상태와 사용자의 지시에 대한 효과를 보여주어
- 사용자가 명령에 대한 진행 상황과 표시된 내용을 해석할 수 있도록 도와주는 것

## NUI(Natural User Interface)
- UI의 종류로, 멀티터치, 동작인식 등 **자연스러운 움직임**을 인식하여 서로 주고받는 정보를 제공하는 사용자 인터페이스

- CLI, GUI, AUI(음성)

## 소프트웨어 모델링
- 모델링 작업의 결과물은 **다른 모델링 작업에 영향을 줄 수 있다.**
- 구조적 방법론에는 DFD(Data Flow Diagram), DD(Data Dictionary)등을 사용하여 요구사항의 결과를 표현한다.
- 객체지향방법론에는 UML표기법을 사용한다.
- 소프트웨어 모델을 사용할 경우, 개발될 소프트웨어에 대한 이해도 및 이해 당사자 간의 의사소통 향상에 도움이 된다.

## 객체지향 분석방법론(완전 중요)
- **Rumbaugh(럼바우) 방법**
  - **객**체 모델(객체), **동**적 모델(상태), **기**능 모델(DFD)
- Booch(부치) 방법
  - 미시적, 거시적 개발 프로세스 모두 사용
- Jacobson 방법
  - **Use Case사용**
- Coad와 Yourdon 방법
  - E-R 다이어그램을 사용하여 객체의 행위를 모델링
- Wirfs-Brock 방법(잘 안나옴)
  - 분석과 설계 간 구분 없음

## Use Case Diagram(완전 중요, 클래스 다이어그램도 중요!)
- 시스템과 상호작용하는 외부시스템은 액터로 파악해야한다.
- 유스케이스는 사용자 측면에서의 요구사항으로, 사용자가 원하는 목표를 달성하기 위해 수행할 내용을 기술한다.
- 시스템 엑터는 다른 프로젝트에서 이미 개발되어 사용되고 있으며, 본 시스템과 데이터를 주고받는 등 서로 연동되는 시스템을 말한다.
- 액터가 인식할 수 없는 시스템 내부의 기능을 하나의 유스케이스로 파악해서는 안된다.

## 소프트웨어 아키텍처 모델 중 MVC(Model-View-Controller)개념
- MVC모델은 사용자 인터페이스를 담당하는 계층의 응집도를 높일 수 있고, 여러개의 다른 UI를 만들어 그 사이에 결합도를 낮출 수 있다.
- 뷰는 모델에 있는 데이터를 사용자 인터페이스에 보이는 역할을 담당한다.
- **제어(Controller)는 모델에 명령을 보냄으로써 모델의 상태를 변경할 수 있다.(납득이 안되지만, 암기할것)**
- 모델은 단순히 데이터에 불과하다!

## 아키텍처 패턴 종류
- 계층화 패턴 (Layered pattern)
- 클라이언트-서버 패턴(Client-Servce Pattern)
- 마스터-슬레이브 패턴(Master-slave pattern)
- 파이프-필터 패턴(Pipe-filter pattern)
- 브로커 패턴(Broker patter)
- 피어 투 피어 패턴(Peer-to-peer pattern)
- 이벤트-버스 패턴(Event-bus pattern)
- 모델-뷰 컨트롤러 패턴(Model-View-Controller patteren)


