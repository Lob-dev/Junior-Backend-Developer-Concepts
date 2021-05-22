
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

> 제가 생각해본 질문과 구글에서 가져올 수 있었던 질문을 모아 정리하였습니다. 잘못된 내용이 있을 수 있으니 개선 요청을 부탁드립니다.

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

## Web

- Http 멱등성에 대해 설명해주세요.
- get은 무엇이고 어느 상황에 주로 사용하나요?
- put과 patch는 무엇이고 각각 언제 사용되나요?
- Cookie와 Session 방식은 어떠한 차이점을 가지나요?
- JSON이란 무엇인가요?
- JWT란 무엇인가요?
- HTTP API는 무엇을 만족해야 RESTful한 API 라고 부를 수 있나요?
- User라는 리소스가 하위로 item이라는 리소스를 가지고 있습니다. 이를 조회해야할 때 RESTful하게 URL을 설계한다면 어떤 모습의 URL에 GET을 요청하게 되나요?
- 3 Way Handshake와 4 Way Handshake는 무엇인가요?
- 3 Way Handshake는 왜 3번 요청을 주고 받는 것인가요?
- TCP/IP와 UDP의 차이는 무엇인가요?
- HTTPS는 무엇인가요?
- Stateless와 Stateful의 차이점은 무엇인가요?
- Servlet은 무엇이고 CGI와 어떠한 차이점을 가지나요?
- WAS는 무엇인가요?
- Buffer와 Stream 방식은 각각 무엇인가요? 실시간으로 처리할 필요가 없는 데이터에 대해서 어떤 방식을 사용하는 것이 효율적일까요?



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
