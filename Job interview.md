
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

[주니어 개발자를 위한 취업 정보](https://github.com/jojoldu/junior-recruit-scheduler)

[매일 업데이트 되는 IT 채용 일정](https://korecruit.kr/)

---

# 면접 질문

> 제가 생각해본 질문과 상시 면접에서 경험한 질문들 그리고 자주 공유되는 질문들을 모아 정리하였습니다. 신입 공채 ~ 주니어 상시까지 정리되었기 때문에 본인의 지식 수준 등을 파악하는데 도움이 될 것이라고 생각합니다.

<br/>

## Java

- Managed - Unmanaged 언어의 차이는 무엇이고 어떤 장, 단점이 있나요?
- Java 접근 제어자에는 무엇이 있는지 설명해주시고 Protect와 Private는 어느 시점에 어떻게 사용될 수 있는지 이야기 해주세요.
- JVM의 메모리 구조에 대해서 설명해 주세요.
- JVM은 어떤 방식으로 코드를 해석하고 실행시키는지 흐름에 맞게 설명해 주세요. (Java 실행 흐름)
- Garbage Collector은 무엇이고, Parallel GC와 CMS GC, G1 GC의 큰 차이는 무엇인지 설명해주세요. (mark-sweep-compact, concurrency-sweep, garbage-first)
- Java 8 버전에 추가된 중요 기능들에 대하여서 설명해주세요.
- Java는 Call By Value일까요, Call By Reference 일까요?
- Shallow Copy와 Deep Copy의 차이는 무엇인가요? 자바에서 Deep Copy를 하기 위해서는 무엇을 사용하여야 하나요?
- Java Reflection이란 무엇이고, 어떨 때 사용되는 것인가요?
- Java Instrumentation이란 무엇이고 사용했을 때 어떤 장점이 있을까요?
- Java Stream API의 특징은 무엇이 있나요?
- Java Lambda는 왜 만들어졌고, 어느 때 주로 사용할까요?
- Java의 Functional interface는 무엇인가요?
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
- Interface와 Abstract Class의 차이는 무엇인가요?
- Interface가 사용되면 좋은 시점은 언제일까요?
- Abstract Class가 사용되면 좋은 시점은 언제일까요?
- Interface와 Abstract Class를 같이 상속받는 경우에는 왜 그렇게 작성하였을까요?
- 데이터 직렬화(Serialization)과 역직렬화(Deserialization)에 대해서 설명해 주세요.
- Java Serialization은 왜 만들어졌고, 어떤 단점들이 있을까요?
- Java Generic에 대해서 설명해 주세요.
- Java Generic의 반공변, 공변, 무공변은 무엇인지 설명해주세요.
- "재 정의된" equals와 ==의 차이는 무엇인가요?
- hashCode의 의미는 무엇인가요?
- 문자열을 리터럴(`string = "abcd"`)로 할당하는 것과 객체(`string = new String("abcd")`)로 할당하는 방식의 차이가 무엇인가요?
- 객체 지향 프로그래밍을 왜 사용한다고 생각하시나요?
- Array와 ArrayList의 차이점은 무엇인가요?
- LinkedList와 ArrayList의 차이점은 무엇인가요?
- Java Compiler는 문자열 연산 최적화를 어떻게 진행하나요? (String Builder, String...)
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

- Spring이란 무엇인가요? Spring이 이야기하는 장점에는 무엇들이 있을까요? (EJB와 비교해서 설명하면 좋을듯) 
- IoC, DI는 무엇이고 어떠한 장점이 있을까요?
- Spring IoC Container란 무엇인가요?
- Spring, Spring Boot의 차이점에 대해 각각 설명해 주세요.
- Spring Boot가 해결하려고 했던 문제는 무엇이고 어떻게 해결하였나요?
- Bean이란 무엇인가요?
- Bean Scope와 종류에 대해 아는 만큼 설명해주세요.
- Configuration은 어떻게 Bean을 등록하고 관리할까요? (Singleton을 지키는 매커니즘은?)
- Bean Lite Mode는 무엇인가요?
- Spring Bean Life-cycle에 대해서 말해주세요.
- @Bean과 @Component은 각각 언제 사용되고 어떤 차이점을 가지나요?
- 순환 참조는 무엇이고 어떤 상황에서 발생할까요?
- Spring으로 개발하실 때 어떠한 DI 방식을 사용하시나요? 사용하는 이유는 무엇이 있는 것일까요?
- Field Injection를 왜 사용하면 안된다고 하는 것인가요? 사용할 때 어떠한 단점이 있을까요?
- (Field 주입과 대비하여) 생성자 주입은 빈 생성 때 사용되는 리플랙션 외에 추가적인 리플랙션을 진행하나요?
- Interceptor와 Filter의 차이점을 말해주세요.
- 스프링에서 Bean으로 Filter를 구현할 수 있을까요? 혹시나 가능하다면 어떻게 할 수 있을까요?
- Message Converter는 어느 시점에 사용되고 어떤 기능을 제공하나요?
- Value Object, Data Transfer Object, Data Access Object 대해서 각각 설명해 주세요.
- Spring AOP는 어떻게 동작할까요? (프록시는 언제 생성되고 요청은 어떻게 잡아내나요?)
- Spring AOP는 CTW, PCW, LTW, RTW 중에 무엇일까요?
- Dynamic Proxy의 CTW, BTW, LTW, RTW은 각각 어떤 시점에 개입하는 것일까요?
- (Spring AOP와 비교하여) AspectJ의 도입 시점은 어느 시점이 될까요? 본인 만의 생각을 알려주세요.
- @Transactional를 스프링 Bean 메서드 A에 적용하였고, 해당 Bean의 메서드 B가 호출되었을 때 메서드 내부에서 메서드 A를 호출하면 어떤 요청 흐름이 발생하게 되나요?
- MVC 1, 2 개념에 대해서 설명해 주세요.
- Front Controller Pattern은 무엇인가요?
- Dispatcher Servlet이란 무엇인가요?
- Spring MVC에서 HTTP 요청이 들어왔을 때의 흐름을 설명해 주세요.
- A 라는 Service 객체의 메서드가 존재하고 내부에서 로컬 트랜잭션이 3개가 존재한다고 할 때, @Transactional을 A 메서드에 적용하였을 때 어떠한 일이 벌어지고, 어떤 요청 흐름이 발생하게 되나요?
- Reflection API는 Runtime에서 코드를 생성하는데 많이 사용됩니다. 이는 Spring에서도 자주 활용되는데요. 스프링 컨테이너는 이런 Reflection으로 생성된 Bean의 정보를 실행 이후에 알고 있네요? 어떻게 알 수 있을까요?

<br/>

---

<br/>

## ORM - JPA

- ORM Framework가 무엇인지 설명해주세요.
- ORM Framework와 Query Mapping Framework의 차이에 대해서 설명해주세요. (JPA vs Mybatis)
- ORM Framework가 해결하는 Object–relational impedance mismatch 이 무엇인지 아는 만큼 설명해주세요.
- Hibernate가 제공하는 Cache 방식들에 대해서 아는 만큼 설명해주세요.
- JPA의 준 영속 상태와 영속 상태에 대해서 설명해주세요.
- JPA Persistence Context이 무엇인지 설명해주시고 제공하는 기능에 대해서 설명해주세요.
- JPA MappedSuperclass와 Embeddable Annotation의 차이는 무엇이고 각각 언제 사용해야 되는지 설명해주세요.
- JPA의 Fatch 전략 대해서 설명해주세요.
- JPA의 Bulk Data Operations에 대해서 설명해주세요.
- JPA의 Bulk Data Operations을 이용하였을 경우 발생하는 문제에 대해서 아는만큼 설명해주세요.
- JPA N+1 문제가 언제 발생하는지 아는 만큼 설명해주세요.
- JPA N+1 문제를 해결하는 방법들을 아는 만큼 설명해주세요.
- Entity와 Value Object를 구분 지을만한 요소가 무엇이 있을지 말씀해주세요. (무엇이 엔티티로 선언되고, 무엇이 벨류 오브젝트로 선언되는지? 그 구분점은?)
- QueryDSL 같은 JPQL Builder를 사용하는 이유를 설명해주세요.

---

<br/>

## Web

- HTTP 멱등성에 대해 설명해주세요.
- get은 무엇이고 어느 상황에 주로 사용하나요?
- put과 patch는 무엇이고 각각 언제 사용되나요?
- Cookie와 Session 방식은 어떠한 차이점을 가지나요?
- JSON이란 무엇인가요?
- Local, Global, Distributed Session에 대해서 아는 만큼 설명해주세요.
- JWT란 무엇인가요? 왜 사용하게 되는 것인가요?
- 구현된 HTTP API는 어떠한 요소들을 만족해야 RESTful한 API 라고 부를 수 있나요?
- User라는 리소스가 하위로 item이라는 리소스를 가지고 있습니다. 이를 조회해야할 때 RESTful하게 URL을 설계한다면 어떤 형태의 URL에 GET을 요청하게 되나요?
- 3 Way Handshake와 4 Way Handshake는 무엇인가요?
- 3 Way Handshake는 왜 3번 요청을 주고 받는 것인가요?
- TCP/IP와 UDP의 차이는 무엇인가요?
- HTTPS는 무엇인가요?
- Stateless와 Stateful의 차이점은 무엇인가요?
- Servlet은 무엇이고 CGI와 어떠한 차이점을 가지나요?
- WAS는 무엇인가요?
- Buffer와 Stream 방식은 각각 무엇인가요? 실시간으로 처리할 필요가 없는 데이터에 대해서 어떤 방식을 사용하는 것이 효율적일까요?
- CIDR이 무엇인지 아시나요?

<br/>

---

<br/>

## Etc.

- 프레임워크와 라이브러리 차이는 무엇인가요?
- 디자인 패턴이란 무엇인가요?
- Monolitc Architecture, Micro Service Architecture에 대해 각각 설명해 주세요.
- Thread-safe한 프로그래밍이란 어떤 것인가요?

<br/>

## DB.

- 인덱스는 왜 사용하는 것인가요?
- 인덱스는 크게 Hash 인덱스와 B-Tree 인덱스가 있습니다. 어떠한 차이가 있을까요?
- B-Tree 인덱스와 B+-Tree 인덱스의 차이는 무엇인가요?
- Transcational의 ACID 속성에 대해서 아시나요?
- 인덱스 Scan 방식은 무엇이 있나요?
- 클러스터 인덱스와 논클러스터 인덱스는 어떤 차이가 있나요?
- 인덱스 설계시 NULL값은 고려되야 할까요?
- 좋은 인덱스를 설계하기 위해 고려해야 하는 조건으로는 무엇이 있는지 아시나요?
- Nested Loop 조인은 무엇일까요?
- 데이터베이스 레플리케이션이 무엇이고 왜 사용하는지 아시나요?
- 데이터베이스 레플리케이션의 실행 방식을 설명해주세요. (MySQL 기준)
- 데이터베이스 레플리케이션시 발생하는 문제점은 무엇이 있을까요?
- 데이터베이스 정규화와 역정규화는 무엇인가요?
- 데이터베이스 파티셔닝은 무엇인가요?
- 데이터베이스 샤딩은 무엇이고 어떤 종류가 있는지 아시는데로 말씀해주세요.
- 레인지 샤딩과 모듈러 샤딩은 무엇이고 어느 장, 단점이 존재하나요?
- 인덱스 샤딩에 대해서 아시나요?
- 2-Phase Commit이 무엇인지 아시나요?
- 많은 사용자들에게 News feed를 제공하는 서비스가 있고, 주간 인기 Feed를 보여주는 것과 일간 Feed를 보여주는 페이지가 있다고 가정할 많은 량의 읽기 트래픽이 존재한다면 어떻게 대처할 수 있을지 말씀해보세요. (주간 인기 Feed에 대한 대처와 일간 Feed에 대한 대처)

---

## Infra.

- On-Premise 환경은 무엇인가요?
- On-Premise와 비교하여 Cloud 환경의 장점과 차이는 무엇인가요? 그리고 On-Premise의 단점은 무엇인가요?
- VM 환경과 Container 환경의 차이는 무엇인가요? 무슨 장점을 가지나요?
- Docker 환경에서 제공되는 Port Forwarding 에 대해서 아시는지, 왜 사용하는지 아시나요?
- Docker Network란 무엇인가요?
- Docker Image를 통한 배포가 기존 배포 방식(VM 이나 Web Server, CGI process 등으로 제공하는 것)에 비해서 얻는 이점이 무엇인지 설명해주세요.
- CIDR을 사용하는 이유에 대해서 아시나요?
- AWS VPC가 무엇인지 아시나요?
- Public VPC Subnet과 Private VPC Subnet이 무엇인지 설명해주시고 왜 이렇게 구조가 분리 되어야 하는지 설명해주세요.
- AWS VPC Peering이 무엇이고 왜 사용하는 것인지 아시나요?
- Service Discovery가 무엇인지 아시나요?
- Load Blancer가 무엇이고 무슨 역할을 하는지 아시나요? 
- SPoF(Single Point of Failure) 에 대해서 아시나요?
- Active-Stand by 모델이 무엇인지 아시는데로 설명해주세요.
- Automatic Leader Election (리더 선출 알고리즘)이 무엇인지 아시나요?
- Redis에 대해서 아시는 만큼 설명해주세요.
- Redis Persistence의 종류로는 무엇이 있나요?
- Redis Sentinel이 무엇인지 아시나요?
- Redis Cluster가 무엇인지 아시나요?
- Message Broker가 무엇인지 아시나요?
- CDN이 무엇인지 아시나요?
