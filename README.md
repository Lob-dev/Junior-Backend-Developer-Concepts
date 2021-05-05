# Junior-Back-end-Developer-Concepts
신입 개발자가 추천하는 자바, 스프링 학습 자료 Repo 입니다. Youtube, Github, Blog 등에서 가져온 여러 소스들과 서적들을 정리하고 있습니다.


---

**개정 이력**

2021.04.29 14:01 : 공통, 자바, 객체 지향, 스프링 추가 (서적, 인강, 참고로 구분)

2021.04.29 14:47 : 내용 보강

2021.04.30 16:07 : 내용 보강 (자바 서적 추가, 스프링 질문 5개 추가)

2021.05.03 01:58 : 개인적으로 추천하는 학습 흐름 추가

2021.05.03 11:30 : 서적 관련 설명 추가, 문서 포맷 변경, Java 면접 질문 강화. SQL 과 설계 항목 템플릿 추가 

2021.05.05 00:14 : 각각의 설명 수정, 내용 보강

---

*내용 추가, 정정 요청은 오픈 프로필, 채팅 방에서 바보 개발자 Lob에게 혹은 해당 Repo에 이슈로 남겨주시길 바랍니다.*

> Optional은 필수는 아니지만, 정말 좋은 (활용 ~ 심화 수준의) 서적을 나타내는 요소입니다. 상황에 따라 학습하지 못하실 수 있지만, 추후에는 한번 즈음은 빌려서라도 보시는 것을 추천 드립니다.

## 공통

### Blog

[참고하는 Blog 링크](https://www.notion.so/Blog-b0c70cc7794b4eb991b76bd7e8766a5b)

[Java, Spring and Web Development tutorials](https://www.baeldung.com/)

### 영상

[우아한테크코스 테코톡 Youtube](https://www.youtube.com/playlist?list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH)

[Amigoscode Youtube](https://www.youtube.com/user/djdjalas)

[[Oracle Code Seoul 2017] Java 9과 Spring 5로 바라보는 Java의 변화와 도전](https://www.youtube.com/watch?v=BFjrmj4p3_Y&t=1277s)

[박재성님 Youtube](https://www.youtube.com/channel/UCGmYJSYFM19VgwEQJsY12Dg)

[brave-people/Dev-Event](https://github.com/brave-people/Dev-Event)

[Sk techx Tacademy](https://www.youtube.com/channel/UCtV98yyffjUORQRGTuLHomw)

---


# 자바

<br/>

## 서적


### 자바 **기본서**

- ***이것이 자바다** - 자세한 개념 설명과 예제가 무난한 책이라고 합니다. 자주 추천되는 책입니다.* 

<br/>

- ***혼자 공부하는 자바** - 이것이 자바다 저자님이 저술하신 서적입니다. 이것이 자바다보다 좀 더 자세하고 쉬운 설명과 예제를 포함하고 있는 책이라고 합니다.*

<br/>

- ***자바의 정석** - Java API를 옮겨온 것 마냥 수많은 예제가 있고 개념 설명들이 잘 되어있는 편입니다.  이 책 또한 자주 추천되는 책입니다.*

<br/>

- ***자바의 신** - 일반적인 자바 기본서와 다른 느낌을 받은 책입니다. 최대한 쉽게 설명하려한 티가 나는 편이고 (아재) 개그가 포함되어 있으며, 각 장의 정리 문제가 좋습니다.*

<br/>

- ***자바 마스터북** - 자바에서 사용되는 필수 개념, 멀티 스레딩과 같은 개념을 정리하고 있고, API 부분과 관련하여선 어떤 문제가 있었고, 버전에 따라 작성 방식이 어떻게 바뀌었는지 비교해주는 책입니다. 앞선 책들보다 깊이는 얕은 느낌이지만 나쁘진 않았습니다.*

<br/><br/>


### **자바 성능 튜닝 이야기**

- *자바에서 성능과 관련된 기본적인 개념들을 집약해놓은 책 입니다. String, System.out, Reflection API, Collection API 등 여러 부분에 기본적인 최적화 방법, 성능 지표, 예제 등이 수록되어 있습니다. 내용도 다루는 것에 비해서 꽤나 쉽게 작성되어 있다고 생각합니다.*

<br/>

### **JVM Performance Optimizing 및 성능 분석 사례 (Optional)**

- *우선적으로 JDK 1.7과 8버전의 JVM 변경 사항을 비교하며, JVM 메모리 명령어와 Root Set, Garbage와 같은 GC의 기본 개념, GC 방식들을 설명해주고 자바의 기본적인 스레드 개념과 동기화 모델을 설명해 줍니다. 중간부터는 JVM 튜닝과 관련된 내용과 튜닝 사례들도 수록되어 있는 좋은 책입니다.*

<br/>

### **이펙티브 자바**

- *자바 계의 명서로 불리는 이펙티브 자바입니다. 기본적인 디자인 패턴부터 시작하여 메서드 작성 방식, 람다와 스트림, 직렬화, 동시성 개념이나 인터페이스 등에 대해 여러 관점이나 안티 패턴인 이유, 각각의 주요 개념 등을 알려줍니다.*

<br/>

### **모던 자바 인 액션 or Practical 모던 자바 (Optional)**

- ***모던 자바 인 액션** - JDK 8~10에 추가된 기능들을 개념과 난이도가 있는 다양한 예제를 통해 설명하는 책입니다. 번역의 질은 조금 떨어지는 것 같지만 좋은 책임은 분명한 것 같습니다.*

<br/>

- ***Practical 모던 자바** - JDK 8~14에 추가된 각각의 기능들이 생겨난 이유와 개념을 설명하고 예제를 포함하고 있습니다. 예제 코드에서 오타도 발견되는 편이지만 읽기에는 무리가 없다고 생각이 듭니다.*

<br/>

### **자바 최적화 (Optional)**

- *초반에 JVM을 학습하기 전에 이해할 수 있도록 기본적인 CS를 다뤄주고 GC의 기본적인 개념부터 심화 개념과 JIT 컴파일러나 컴파일러 최적화 등을 설명합니다. 번역의 질은 조금 떨어지지만 자체로는 좋은 서적입니다.*

<br/>

### **자바 병렬 프로그래밍 (Optional)**

- *이 책 또한 자바 계의 명서중 하나입니다. 동시성의 기본 원리와 스레드 개념부터 자바에서 동기화와 관련된 여러 요소와 병렬 구조, 명시적인 락, 동시성 API를 다루고 있습니다. 오래된 책이지만 아직도 적용할 만 한 것들과 개념, 예제들이라고 생각합니다.*

<br/>

---

<br/>

## 인강

### 프로그래머스 자바 입문, 중급 (Optional)

- *좋은 품질의 무료 강의로 생각되어 추천합니다. 기본서를 통한 개념 정리 시 병행하기에 좋습니다.*

<br/>

### 자바의 정석 기초편 (Optional)

- *자바의 정석 저자가 기초 편을 기반으로 만들어낸 입문 강의. 위에 작성된 강의와 비교하여 본인에게 맞는 강의를 진행하는 것을 추천합니다.*

<br/>

### 인프런 Java Playground Level 1 (Optional)

- *개념, 이론의 선행보다는 요구사항과 예제를 통해 자바를 학습하도록 설계된 좋은 강의입니다. 이 또한 본인에게 맞는 경우 진행하시면 될 것 같습니다.*

<br/>

### 더 자바 Java 8 (Optional)

- *백기선 님이 Java 8에 추가된 굵직한 기능들에 대해 예제 기반의 학습, 설명을 진행하십니다. 난이도가 조금 있는 편이라고 생각하기에 기본서 학습 후 들어보는 것을 추천합니다. 아니면 참고 링크에 작성된 모던 자바 8 못다 한 이야기를 보셔도 좋을 것 같습니다.*

<br/>

### 더 자바, 코드를 조작하는 다양한 방법 (Optional)

- *백기선 님이 자바 기반 라이브러리, 프레임워크에서 사용하는 핵심적인 기능인 Bytecode generation, Reflection API, Annotation, Dynamic proxy를 설명해주는 강의입니다. 난이도가 조금 있는 편이나. 기본서 학습 후 듣는 것을 추천합니다.*

<br/>

***개인적으로 중요한 자바 개념이라고 생각하는 것들***

*JVM Stack, Heap, 동시성과 상태, JDK Dynamic Proxy, Collection API*, *Reflection API, Annotation, Class, this, Interface*

<br/>

---

## 참고

[모던 자바 (자바 8) - 못다한 이야기](https://www.youtube.com/playlist?list=PLRIMoAKN8c6O8_VHOyBOhzBCeN7ShyJ27)

[자바의 정석 기초편 - 객체지향개념만](https://www.youtube.com/playlist?list=PLW2UjW795-f5JPTsYHGAawAck9cQRw5TD)

---

<br/>

# 객체 지향, 디자인 패턴

## 서적

### 한 번 읽으면 두 번 깨닫는 객체 지향 프로그래밍 (Optional)

- *객체 지향 개념을 예제와 도식을 이용하여 쉽게 설명하는 서적입니다. 객체 지향 입문 시 무난한 서적이라고 생각합니다.*

<br/>

### 객체 지향의 사실과 오해 (Optional)

- *기존 자바, 기타 서적에서 이론적으로 설명하는 객체 지향을 소설 이상한 나라의 앨리스를 이용하여 풀어 설명하는 책입니다. 별도의 코드 없이도 객체 지향 개념을 바로잡고 깊게 이해할 수 있도록 하기에 추천합니다.*

<br/>

### 개발자가 반드시 정복해야 할 객체 지향과 디자인 패턴 (Optional)

- *해당 서적과 관련하여 후기를 알려주시면 감사드리겠습니다.*

<br/>

### 실전 코드로 배우는 실용 주의 디자인 패턴 (Optional)

- *객체 지향과 디자인 패턴을 다루는 서적입니다. 개인적으로 객체 지향의 중요한, 좋은 내용을 담고 있다고 생각합니다. 일반적인 서적에서 다루지 않는 게터와 세터, 캡슐화, 추상화 등에 관한 이야기를 다루고 소형 DB, 생명 게임이라는 난이도 있는 예제를 포함하고 있습니다. 부록으로 각 디자인 패턴을 한 장으로 요약하여 정리하고 있습니다. 해당 서적은 중고로 구매 가능합니다.*

<br/>

### 오브젝트 (Optional)

- *객체 지향의 사실과 오해를 저술하신 저자님의 서적입니다. 예제 코드와 ERD를 통해 개념을 설명하고 비교, 개선하면서 더 나은 객체 지향 설계를 보여줍니다. 난이도가 있다고 생각됩니다.*

<br/>

---

## 인강

### 인프런 객체 지향 프로그래밍 입문

- *객체의 4대 속성과 상속보단 조합, DI를 예제와 함께 설명해주는 좋은 강의라고 생각합니다.*

<br/>

***개인적으로 중요한 객체 지향 개념이라고 생각하는 것들***

*상속과 조합, 객체의 상태, 역할, 메세지, 다형성, 의존 관계, 설계의 유연성* 

<br/>

---

## 참고

[객체지향 프로그래밍이 뭔가요? Youtube](https://www.youtube.com/watch?v=vrhIxBWSJ04&t=119s)

[Design Patterns in Object Oriented Programming Youtube](https://www.youtube.com/playlist?list=PLrhzvIcii6GNjpARdnO4ueTUAVR9eMBpc)

[OOP는 중요하다. 하지만... Youtube](https://www.youtube.com/watch?v=7zz5gKa7iXk&t=58s](https://www.youtube.com/watch?v=7zz5gKa7iXk&t=58s))

[함수형 프로그래밍 Youtube](https://www.youtube.com/watch?v=XoH9jzblxKQ)

[OOP는 허접한 개발자 때문에 발전했다? Youtube](https://www.youtube.com/watch?v=oHaGgLRZy3Y&t=5s)

---

<br/>

# 스프링 Core, MVC


> Cloud 쪽은 아직 학습 중이기 때문에.. 추후에 추가할 예정입니다.

## 서적

### 스프링 입문을 위한 자바 객체 지향의 원리와 이해

<br/>

### 코드로 배우는 스프링 부트 웹 or 처음 배우는 스프링 부트 2 or 스프링 인 액션

- *코드로 배우는 스프링 부트 웹 : 입문 용으로 추천하는 서적의 개정판입니다. 레거시 스프링과 마이바티스를 다루던 이전 버전과 달리 부트와 JPA를 사용하였습니다..*

<br/>

- **처음 배우는 스프링 부트2 : Spring Boot 모듈의 의존성 관리, 자동 설정. 테스트 환경 등을 설명하며 게시판 예제를 통해 Oauth2, Security, RESTful, Batch 등의 기본적인 개념과 예제를 다룹니다.*

<br/>

- *스프링 인 액션 : 믿고 본다는(?) 인 액션 중 하나. 스프링 개발자 중 한명 인 저자가 애플리케이션을 개발해 나가면서 이용해 여러 전반적인 개념을 학습하도록 합니다.*

<br/>

### 토비의 스프링 (Optional)

- *스프링 생태계의 명서. 객체 지향과 설계 관점으로 Spring을 바라보고 해설하는 서적입니다. 난이도가 있지만 객체 지향과 설계를 이해하려고 할 때 보기에 좋다고 생각합니다.*
- *3.1이라는 과거 버전의 스프링을 다루었지만 5.x 버전까지 그 근본이 바뀌지 않았고 몇몇 구현체도 개선되었을 뿐 큰 틀은 변경되지 않았기에 보는 것을 추천합니다.*

<br/>

### Spring MVC Programming (Optional)

- *Spring 개발자들이 Spring MVC 만을 다룬 서적입니다. MVC의 주요 구현체와 요청 흐름, 각각의 Annotation을 설명하고 예제를 통해 정리합니다. 4.x 버전의 스프링을 사용합니다.*

<br/>

### 전문가를 위한 Spring (Optional)

- *여러 개발자들이 추천하는 서적 중 하나. 스프링의 전반적인 내용들을 5.x 버전 기준으로 설명합니다.*
- *타 개발자에게 추천 받은 것이라 상세한 후기를 기다리고 있습니다.*

<br/>

---

## 인강

### 인프런 김영한님 스프링 입문 강의

- *무료 강의 중에서 Spring MVC에 대한 큰 요청 흐름을 설명하고 간단하게 구현해보는 좋은 강의라고 생각합니다.*

<br/>

### 이도원님 RESTful API (Optional)

- *RESTful 형식의 Spring API 구현해볼 수 있는 좋은 강의입니다. RESTful을 이해하는데 큰 도움이 된다고 생각합니다.*

<br/>

### 인프런 김영한님 스프링 핵심원리 기본 (Optional)

- *Spring의 핵심적인 사상과 기능들을 간단하게 설명해주는 좋은 강의입니다.*
- *해당 강의 학습 후 토비의 스프링을 학습하면 좀 더 수월한 학습이 가능할 것이라고 생각합니다.*

<br/>

### 인프런 김영한님 스프링 핵심원리 MVC (Optional)

- *Spring MVC의 핵심적인 개념과 기능을 학습하고 예제 구현을 통해 리팩토링과 설계에 대한 인사이트를 제공하는 좋은 강의입니다.*

<br/>

### 인프런 백기선님 RESTful API (Optional, +TDD)

- *좀 더 확실한 RESTful 개념을 학습할 수 있는 강의라고 생각합니다. TDD를 통해 개발하는 것 때문에 좀 더 추천하기도 합니다. 올바른 RESTful 은 무엇을 준수해야하고, TDD를 통한 개발은 어떻게 진행되는지 인사이트를 얻을 수 있습니다.*

<br/>

***개인적으로 중요한 스프링 개념이라고 생각하는 것들***

IoC와 DI, PSA, *CoC, CGLIB, AOP, Dispatcher Servlet (Front-Controller Pattern), Annotation Processor, Delegate Pattern,  Strategy pattern, Proxy pattren*

<br/>

---

## 참고

[데어 프로그래밍 Youtube](https://www.youtube.com/channel/UCVrhnbfe78ODeQglXtT1Elw)

[나무소리 Youtube](https://www.youtube.com/channel/UCtaUzBujIBjtrkqACmkM44g)

[토비의 봄 TV 14회 스프링 리액티브 프로그래밍 (10) Flux의 특징과 활용방법 Youtube](https://www.youtube.com/watch?v=bc4wTgA_2Xk&list=PLv-xDnFD-nnmof-yoZQN8Fs2kVljIuFyC)

[백기선님 Youtube](https://www.youtube.com/channel/UCwjaZf1WggZdbczi36bWlBA)

[cheese10yun/spring-guide](https://github.com/cheese10yun/spring-guide)

[Day1, 2-2. 그런 REST API로 괜찮은가? Youtube](https://www.youtube.com/watch?v=RP_f5dMoHFc&t=619s&ab_channel=naverd2)

---

<br/>

# SQL, DB

<br/>

# 설계, 클린코드

<br/>

# 개인적으로 추천하는 입문 학습 흐름

## 자바 입문부터 스프링 입문까지

<br/>

### **자바 기본서 항목 1독**

- [https://lob-dev.tistory.com/entry/Java의-Reflection-API](https://lob-dev.tistory.com/entry/Java%EC%9D%98-Reflection-API)

<br/>

### **객체 지향의 사실과 오해**

<br/>

### **SQL 첫걸음 혹은 기타 SQL 책**

- *CRUD, Local or Global transaction, DDL 기본 , Index*
- *대부분의 서비스는 CRUD를 무조건적으로 포함한다고 봐야됩니다. 이는 게시판 같은 것에 특정 되는 개념이 아니라 모든 데이터를 다룸에 있어서 통용되는 것입니다.*
- *트랜잭션, 인덱스 개념은 개발자에겐 필수 개념이라고 생각합니다.*

<br/>

### **Sevlet API (JSP는 제외)**

- *Server - Client Model, HTTP, SSR and CSR, JSON, RESTful API*
- *Servlet은 자바 기반의 "표준" Protocol API이며, HTTP와 기타 Protocol을 처리하는 뼈대가 됩니다. 스프링이나 Vaddin, Struct 같은 프레임워크도 내부적으로는 Servlet을 통해 동작하는 기능들이 있습니다. 자바 기반의 웹 근본 개념 이해를 위해 우선하여 학습하는 것을 추천합니다.*
- [https://lob-dev.tistory.com/entry/CGI-Servlet-Servlet-Container](https://lob-dev.tistory.com/entry/CGI-Servlet-Servlet-Container)
- [https://lob-dev.tistory.com/entry/01-RESTful-개념과-사전-지식](https://lob-dev.tistory.com/entry/01-RESTful-%EA%B0%9C%EB%85%90%EA%B3%BC-%EC%82%AC%EC%A0%84-%EC%A7%80%EC%8B%9D)

<br/>

### **JDBC API**

- *JDBC는 자바 기반의 "표준" DB 접근 API이며, Mybatis, JPA 와 같은 SQL Mapper, ORM 프레임워크들도 내부적으로는 JDBC의 Connection과 Statement를 사용하기 때문에 이를 통한 애플리케이션 시점에서의 로컬, 글로벌 트랜잭션 방식을 이해하는 것이 개인적으로 중요하다고 생각합니다.*
- [https://lob-dev.tistory.com/entry/Java-Database-Connectivity-알아보기](https://lob-dev.tistory.com/entry/Java-Database-Connectivity-%EC%95%8C%EC%95%84%EB%B3%B4%EA%B8%B0)

<br/>

### **스프링 입문을 위한 자바 객체 지향의 원리와 이해**

- *Spring을 학습하기 이전에 JVM의 메모리, 객체 지향 개념과 구현 방식을 다시 복습할 수 있고, Spring에 적용된 디자인 패턴을 선행 학습할 수 있는 좋은 책입니다.*
- [https://lob-dev.tistory.com/entry/책임을-중시하는-객체-지향-디자인의-핵심-개념-GRASP](https://lob-dev.tistory.com/entry/%EC%B1%85%EC%9E%84%EC%9D%84-%EC%A4%91%EC%8B%9C%ED%95%98%EB%8A%94-%EA%B0%9D%EC%B2%B4-%EC%A7%80%ED%96%A5-%EB%94%94%EC%9E%90%EC%9D%B8%EC%9D%98-%ED%95%B5%EC%8B%AC-%EA%B0%9C%EB%85%90-GRASP)

### **코드로 배우는 스프링 부트 웹 프로젝트**

- *취업이나 상황에 따라 시간이 부족하다면 앞선 책을 건너뛰고 해당 책으로 학습을 하는 것도 추천하기도 합니다. 입문 서적으로는 좋은 책인 것 같습니다.*

<br/>

### **인프런 스프링 입문 - 코드로 배우는 스프링 부트, 웹 MVC, DB 접근 기술**

- *기본적인 Spring Boot 애플리케이션을 경험해볼 수 있는 좋은 입문 강의입니다. MVC 요청 흐름과 템플릿 엔진 등의 개념을 경험해볼 수 있습니다.*

<br/>

### **처음 배우는 스프링 부트 2 (Optional)**

- *Spring Boot 모듈의 의존성 관리, 자동 설정. 테스트 환경 등을 설명하며 게시판 예제를 통해 Oauth2, Security, RESTful, Batch 등의 기본적인 개념과 예제를 다룹니다.*

<br/>

### **개인 프로젝트 진행**

- *앞에서 경험했던 기술들을 본인만의 요구 사항에 녹이고 적용하여 프로젝트를 진행하시면 좋을 것 같습니다.*
- *모든 방식에는 장단점이 존재하기 때문에. 이를 비교하고 설명할 수 있어야한다고 생각합니다. (물론 저는 못합니다..)*
    - *ex) 객체 간의 변환 시에 MapStruct를 사용하셨는데 메서드를 통해 작성하는 방법이나 ModelMapper를 사용하는 방식도 있지 않나요? 왜 MapStruct를 사용하셨는지 설명해주실 수 있으실까요? 등..*

<br/>

**이후는 위에 따로 서술된 항목이나 주변의 추천을 통해 추가 학습 진행**

<br/>

---

<br/>

# 프로젝트

## 참고

[공공데이터 포털](https://www.data.go.kr/)

[public apis - 영어](https://github.com/public-apis/public-apis)

[API란? 개념 정리와 포트폴리오에 유용한 대박 사이트 공유 🙌 Youtube](https://www.youtube.com/watch?v=ogT267HvNuQ&t=337s&ab_channel=%EB%93%9C%EB%A6%BC%EC%BD%94%EB%94%A9by%EC%97%98%EB%A6%AC)

---

<br/>

# 취업, 면접

## 참고

[WooVictory/Ready-For-Tech-Interview](https://github.com/WooVictory/Ready-For-Tech-Interview)

[jojoldu/junior-recruit-scheduler](https://github.com/jojoldu/junior-recruit-scheduler)

[HyeminNoh/Tech-Stack](https://github.com/HyeminNoh/Tech-Stack)

[JaeYeopHan/Interview_Question_for_Beginner](https://github.com/JaeYeopHan/Interview_Question_for_Beginner)

[gyoogle/tech-interview-for-developer](https://github.com/gyoogle/tech-interview-for-developer)

[Febase/FeBase](https://github.com/Febase/FeBase)

[cheese10yun/dev-info](https://github.com/cheese10yun/dev-info)

---

# 면접 질문

> *제가 생각해본 질문과 구글에서 가져올 수 있었던 질문을 모아 정리하였습니다. 잘못된 내용이 있을 수 있으니 개선 요청을 부탁드립니다.*

<br/>

## Java

- Managed - Unmanaged 언어의 차이는 무엇이고 어떤 장, 단점이 있나요?
- Java 접근 제어자에 대해 설명해주시고 Protect와 Private는 왜 사용되는지 이야기 해주세요.
- JVM의 메모리 구조에 대해서 설명해 주세요.
- JVM은 어떤 방식으로 코드를 해석하고 실행시키는지 흐름에 맞게 설명해 주세요.
- Garbage Collector은 무엇이고, Parallel GC와 CMS GC, G1 GC의 큰 차이는 무엇인지 설명해주세요. (mark-sweep-compact, concurrency-sweep, garbage-first)
- Java 8 버전에 추가된 중요 기능들에 대하여서 설명해주세요.
- Java는 Call By Value일까요, Call By Reference 일까요?
- Shallow Copy와 Deep Copy의 차이는 무엇인가요? 자바에서 Deep Copy를 하기 위해서는 무엇을 사용하여야 하나요?
- 리플렉션(Reflection)이란 무엇이고, 어떨 때 사용되는 것인가요?
- Java Instrumentation이란 무엇인가요?
- Java Stream API란 무엇인가요?
- Java Lambda란 무엇인가요?
- Java의 함수형 인터페이스는 무엇인가요?
- foreach를 사용할 수 있는 자료구조는 어떤 인터페이스를 상속 받고 있나요?
- iterator와 iterable 차이는 무엇인가요?
- Fast-fail iterator는 무엇이고 어떤 것을 위해 사용되는 건가요?
- 자바의 synchronized 키워드에 대해 설명해주시고 Reentrant Lock와의 차이는 무엇인지 말씀해주세요.
- Java의 synchronized Lock 범위에 대해서 알려주세요. (Class Lock, Instance Lock)
- volatile 키워드에 대해 설명해 주세요.
- atomic Type과 CAS는 무엇이고 언제 사용되는 것인가요?
- 하나의 쓰기 스레드와 여러 읽기 스레드가 존재할 때 사용되어야 하는 Java의 동기화 기능은 무엇이고 어떻게 동작하게 되는지 설명해주세요.
- 스레드에서 Race condition에 대해서 설명해주세요.
- Java final 키워드에 대해서 설명해주세요. 각각의 쓰임에 따라 어떻게 동작하나요? (Class, Variable)
- String이 final인 이유는 무엇인가요?
- Wrapper Class란 무엇이고 Primitive Type과의 차이는 무엇인가요?
- 객체 지향의 클래스, 객체, 인스턴스 차이에 대해서 설명해 주세요.
- 불변 객체는 무엇이고 Java에서 어떻게 구현할까요?
- 직렬화(Serialization)과 역직렬화(Deserialization)에 대해서 설명해 주세요.
- Java Generic에 대해서 설명해 주세요.
- 반공변, 공변, 무공변은 무엇인지 설명해주세요.
- 재 정의된 equals와 ==의 차이는 무엇인가요?
- hashCode란 무엇인가요?
- 문자열을 리터럴(`string = "abcd"`)로 할당하는 것과 객체(`string = new String("abcd")`)로 할당하는 방식의 차이가 무엇인가요?
- 추상 클래스와 인터페이스의 차이는 무엇이고, 어느 때에 추상 클래스를 사용하고 인터페이스를 사용하실 건지 설명해주세요.
- 객체 지향 방식을 왜 사용한다고 생각하시나요?
- Array와 ArrayList의 차이점은 무엇인가요?
- LinkedList와 ArrayList의 차이점은 무엇인가요?
- 컴파일러는 문자열 연산 최적화를 어떻게 진행하나요? (String Builder, String...)
- SringBuilder를 사용하는 것과 String을 사용하여 연산하는 것에서 어떠한 큰 차이가 존재할까요?
- Stack을 사용하지 못하는 상황에서 대체할 수 있는 Collection은 무엇이 있을까요?
- Vector와 Stack을 사용하지 않는 이유는 무엇인가요?
- Lock Stripping은 무엇이고 어떠한 자료구조가 해당 방식을 구현하였나요?
- HashMap에 대해서 설명해주시고, Hash Collision 발생 시 자바는 어떻게 대처하나요?
- Hash Collision이 많이 발생할 경우 어떤 최적화가 진행될까요?
- ConcurrentHashMap은 어떤 방식으로 스레드 동시성을 보장하나요?
- CopyOnWriteArrayList은 어떤 방식으로 스레드 동시성을 보장하나요?

<br/>

---

<br/>

## Spring

- CGI는 무엇이고 Servlet API는 무엇이며, 어떤 차이가 있나요?
- Spring이란 무엇인가요?
- IoC, DI가 왜 좋은 걸까요?
- IoC Container란 무엇인가요?
- Spring, Spring Boot의 차이점에 대해 각각 설명해 주세요.
- Spring Boot가 해결하려고 했던 문제는 무엇이고 어떻게 해결하였나요?
- Spring Framework의 빈 생명 주기에 대해서 말해주세요.
- 순환 참조는 무엇이고 어떻게 발생하나요?
- 생성자 주입은 빈 생성 때 사용되는 리플랙션 외에 추가적인 리플랙션을 진행하나요?
- Bean이란 무엇인가요?
- Bean Scope와 종류에 대해 아는 만큼 설명해주세요.
- Bean Lite Mode는 무엇인가요?
- @Bean과 @Component은 각각 언제 사용되고 어떤 차이점을 가지나요?
- Interceptor와 Filter의 차이점을 말해주세요.
- 스프링에서 Bean으로 Filter를 구현할 수 있을까요? 혹시나 가능하다면 어떻게 할 수 있을까요?
- Message Converter 와 MV Container는 각각 어떻게 개입하고 어떤 방식으로 동작하나요?
- VO, DTO, DAO에 대해서 각각 설명해 주세요.
- Spring AOP는 어떻게 동작할까요? (프록시는 언제 생성되고 요청은 어떻게 잡아내나요?)
- MVC1, 2 개념에 대해서 설명해 주세요.
- Dispatcher-Servlet이란 무엇인가요?
- Spring MVC에서 HTTP 요청이 들어왔을 때의 흐름을 설명해 주세요.
- Spring AOP는 CTW, LTW, RTW 중에 무엇이고 Aspactj 와 비교하여 언제 사용하는 것이 좋고 언제 사용하지 않는 것이 좋을까요?
- Dynamic Proxy의 CTW, BTW, LTW, RTW은 각각 무엇인가요?
- @Transactional를 스프링 Bean 메서드 A에 적용하였고, 해당 Bean의 메서드 B가 호출되었을 때 메서드 내부에서 메서드 A를 호출하면 어떤 요청 흐름이 발생하게 되나요?
- A라는 Service 객체의 메서드가 존재하고 내부에서 로컬 트랜잭션이 3개가 존재한다고 할 때, @Transactional을 A 메서드에 적용하였을 때 어떠한 일이 벌어지고, 어떤 요청 흐름이 발생하게 되나요?
- Reflection API는 Runtime에서 코드를 생성해내는데 많이 사용되게 됩니다. 이는 스프링에서도 적용되는데요. 스프링 컨테이너는 이런 Reflection으로 생성된 Bean을 알고 있네요? 어떻게 알 수 있을까요?

<br/>

---

<br/>

## Etc.

- 프레임워크와 라이브러리 차이는 무엇인가요?
- 디자인 패턴이란 무엇인가요?
- Monolitc Architecture, Micro Service Architecture에 대해 각각 설명해 주세요.
- Thread-safe한 프로그래밍이란 어떤 것인가요?

<br/>

---
