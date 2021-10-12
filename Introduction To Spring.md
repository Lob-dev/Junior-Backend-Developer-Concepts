
# 개인적으로 추천하는 백엔드 입문 학습 흐름

## 자바 입문부터 스프링 프레임워크를 이용한 첫 프로젝트 개발까지

<br/>

### **자바 기본서 항목 1독**

- 추가 학습 [Reflection API] : [https://lob-dev.tistory.com/entry/Java의-Reflection-API](https://lob-dev.tistory.com/entry/Java%EC%9D%98-Reflection-API)
- 추가 학습 [Annotation] : https://b-programmer.tistory.com/264

<br/>

### **객체 지향의 사실과 오해**

- Java 서적 추천 항목에 포함되어 있는 책으로 객체지향 개념을 바로 잡는데 큰 도움이 되는 책입니다. 

<br/>

### **SQL 첫걸음 혹은 기타 SQL 책 [JDBC 전후로 진행해도 무관합니다.]**

- CRUD, Local or Global transaction, DDL 기본 , Index
- 대부분의 서비스는 CRUD를 무조건적으로 포함한다고 봐야됩니다. (모든 데이터를 다룸에 있어서 통용되는 것입니다.) 여러 교육에서 게시판 형태의 프로젝트를 기본 예제로 자주 사용하는 것도 이러한 맥락입니다. 
- 부가적으로 트랜잭션의 특징과 인덱스 개념은 취업을 하기전 필수 개념이라고 생각합니다. CS 개념 이외에도 애플리케이션단에서 제공하는 관련 API에 대한 기본 학습이 필요합니다. 
- 최근 일정 이상 기업의 면접에서는 샤딩이나 레플리케이션도 질문하는 겅우가 늘어나고 있는데요. 그와 관련한 개념 학습 정도는 해두시는 것이 좋을 것 같습니다. 샤딩의 경우 우아한 형제들 기술 블로그에 잘 정리되어 있습니다.  

<br/>

### **Servlet API (JSP는 제외) [영한님의 MVC 1편으로 어느정도 학습 가능합니다.]**

- Server - Client Model, HTTP, SSR and CSR, JSON, RESTful.. 웹과 관련된 다양한 개념이 많습니다만 현실적으로 JVM 생태계에서 웹 프로토콜을 지원하는 핵심 API는 바로 Servlet입니다.
- Servlet은 자바 기반의 "표준" Protocol API이며, HTTP와 기타 Protocol을 처리하는 뼈대가 됩니다. Spring MVC나 Vaddin, Struct 같은 프레임워크도 내부적으로는 Servlet을 통해 동작하기에 자바 기반의 웹 근본 개념 이해를 위해 우선하여 학습하는 것을 추천합니다.
- 자바에서도 Event Loop를 기반으로하는 비동기 방식 처리를 지원합니다만 아직까지 신입에게 요구하는 회사를 본 것은 손에 꼽을 정도입니다.
- 부가 학습  : [https://lob-dev.tistory.com/entry/CGI-Servlet-Servlet-Container](https://lob-dev.tistory.com/entry/CGI-Servlet-Servlet-Container)
- 추가 학습 자료 : [https://lob-dev.tistory.com/entry/01-RESTful-개념과-사전-지식](https://lob-dev.tistory.com/entry/01-RESTful-%EA%B0%9C%EB%85%90%EA%B3%BC-%EC%82%AC%EC%A0%84-%EC%A7%80%EC%8B%9D)

<br/>

### **CS 보충 학습**

- [서적 : 학교에서 알려주지 않는 17가지 실무 개발 기술](http://www.yes24.com/Product/Goods/89906094)
- [서적 : 그림으로 배우는 HTTP & Network](http://www.yes24.com/Product/Goods/15894097?OzSrank=1)
- 위 서적들은 다양한 개념을 쉽게 다루는 책들입니다. 저도 취업 준비를 할 때 이 서적들을 보면서 막혔던 부분들을 어느정도 해소할 수 있었습니다. 

<br/>

### **JDBC API [Connection Pool, Connection, ResultSet, Statement 집중!]**

- JDBC는 자바 기반의 "표준" DB 접근 API이며, Mybatis, JPA 와 같은 SQL Mapper, 각종 ORM 프레임워크들도 내부적으로는 JDBC API를 사용하기 때문에 이를 통한 애플리케이션 시점에서의 로컬, 글로벌 트랜잭션 방식을 이해하는 것이 개인적으로 중요하다고 생각합니다.
- 적어도 JDBC Template API 수준의 추상화까진 공부해보는 것이 좋다고 생각합니다.
- 부가 학습 자료 : [https://lob-dev.tistory.com/entry/Java-Database-Connectivity-알아보기](https://lob-dev.tistory.com/entry/Java-Database-Connectivity-%EC%95%8C%EC%95%84%EB%B3%B4%EA%B8%B0)

<br/>

### **스프링 입문을 위한 자바 객체 지향의 원리와 이해**

- Spring을 학습하기 이전에 JVM의 메모리, 객체 지향 개념과 구현 방식을 다시 복습할 수 있고, Spring에 적용된 디자인 패턴을 선행 학습할 수 있는 좋은 책입니다.
- 책의 분량에 비해 다루는 내용이 많고 잘 정리되었다고 생각합니다.  
- 추가 학습 자료 : [https://lob-dev.tistory.com/entry/책임을-중시하는-객체-지향-디자인의-핵심-개념-GRASP](https://lob-dev.tistory.com/entry/%EC%B1%85%EC%9E%84%EC%9D%84-%EC%A4%91%EC%8B%9C%ED%95%98%EB%8A%94-%EA%B0%9D%EC%B2%B4-%EC%A7%80%ED%96%A5-%EB%94%94%EC%9E%90%EC%9D%B8%EC%9D%98-%ED%95%B5%EC%8B%AC-%EA%B0%9C%EB%85%90-GRASP)


<br/>

### **인프런 스프링 입문 - 코드로 배우는 스프링 부트, 웹 MVC, DB 접근 기술 [이전 개념들을 어느정도 코드로 구현해볼 수 있고, 템플릿 엔진 개념도 학습 가능합니다.]**

- 기본적인 Spring Boot 애플리케이션을 경험해볼 수 있는 좋은 입문 강의입니다. MVC 요청 흐름과 템플릿 엔진 등의 개념을 경험해볼 수 있습니다.
- 유료 강의를 선행하기 이전에 해당 강의를 수강함으로써 현재 자신의 수준을 파악하고 보충할 수 있는 기회가 될 것이라고 생각합니다. 

<br/>

### **인프런 Spring Boot를 이용한 RESTful Web Services 개발 **

- RESTful API 설계 방식과 JPA를 활용한 데이터 베이스, API 실제 구현 코드를 경험해볼 수 있는 좋은 강의입니다. 최근 강사님이 업데이트를 예정하여 최신 버전도 경험해볼 수 있을 것 같습니다.

<br/>

## 프로젝트 전 추천 학습 서적 (하나만 골라보셔도 충분합니다.)

[ 

<br/>

### **React.js, 스프링 부트, AWS로 배우는 웹 개발 101**

- 정말 기본적인 Web Server와 WAS, Req, Res 요청 흐름, Spring, Layered architecture와 REST API 까지 다양한 개념을 먼저 다루고, TO-DO Application을 Backend에서 Frontend로 차근차근 개발해보는 좋은 책입니다.
- 이후에는 REST API의 인증 기법으로 Basic, Bearer, JSON에 대한 내용을 다루고 JWT 구현체와 Security를 적용하여 로그인 프로세스도 구현해봅니다.
- 마지막으로는 AWS에서 주로 사용되는 리소스를 살펴보고 일라스틱 빈스톡을 이용한 배포를 진행해봄으로써 한 Application이 개발되고 배포되는 그러한 과정을 경험할 수 있습니다.   

<br/>

### **코드로 배우는 스프링 부트 웹 프로젝트**

- 취업이나 상황에 따라 시간이 부족하다면 앞선 책을 건너뛰고 해당 책으로 학습을 하는 것도 추천하기도 합니다. 입문 서적으로는 좋은 책입니다.
- 국비를 통해 교육을 받으신 취준생 분들이라면, 이책에서 ORM과 QueryDSL이 무엇이고 어떻게 사용하는 것인지 경험해볼 수 있다고 생각합니다.

<br/>

### **처음 배우는 스프링 부트 2 (Optional)**

- Spring Boot 모듈의 의존성 관리, 자동 설정. 테스트 환경 등을 설명하며 게시판 예제를 통해 Oauth2, Security, RESTful, Batch 등의 기본적인 개념과 예제를 다룹니다.
- 프로젝트를 진행하기 이전에 좀 더 다양환 기능을 녹여보고 싶으시다면, 해당 책에서 다루는 기능들을 공부하여 추가해볼 수 있을 것이라고 생각합니다. 물론 포트폴리오로 작성하는 프로젝트의 경우 하나하나의 기능들에 대하여서 해당 책보다 더 깊은 이해를 하고 사용하는 것이 좋습니다. 

<br/>

]

<br/>

### **etc : Docker 학습**

- https://subicura.com/2017/01/19/docker-guide-for-beginners-1.html 혹은 기타 링크
- Application 부터 Mysql, Redis, RabbitMQ 등을 별도 가상화 기술 사용 없이 쉽게 개발 환경을 구성하도록 도와줍니다.
- 최근 많은 회사에서 docker와 같은 컨테이너 기반 기술을 이용하여 인스턴스를 생성하고 관리합니다. 
- 다량의 컨테이너를 배포하고 관리하고 스케일 처리하는 것은 오케스트레이션 들을 사용하게 됩니다.

<br/>

### **etc : RESTful 설계 학습**
- 요즘 대부분의 HTTP API는 RESTful 설계 방식을 이용하여 REST API 라고 명명하기도 합니다. 하지만 생각보다 REST의 설계 제약이 빡빡하기 때문에 모두 만족하는 API는 거의 없다고 보아도 좋을 정도입니다.
- 논란이 조금 있을 수 있는 리처드슨의 모델이나, RESTful 설계자인 로이 필딩의 논문 등을 보게된다면 이렇게까지 해야 되는건가? 싶기도 하실탠데 그래도 다 봐두는 것이 좋습니다.
- https://shoark7.github.io/programming/knowledge/what-is-rest 
- https://www.restapitutorial.com/ - 영문 사이트
- https://www.youtube.com/watch?v=RP_f5dMoHFc&t=638s&ab_channel=naverd2 - RESTful API를 학습한다면 필수적으로 보아야할 영상이라고 생각합니다.

<br/>

### **etc : AWS or CLOUD 기본 학습**

- https://www.inflearn.com/course/aws-%ED%81%B4%EB%9D%BC%EC%9A%B0%EB%93%9C-%EC%8B%9C%EC%9E%91%ED%95%98%EA%B8%B0#curriculum 혹은 기타 링크
- http://www.yes24.com/Product/Goods/102368122?OzSrank=4 , http://www.yes24.com/Product/Goods/73363873?OzSrank=21 혹은 기타 서적
- 최근 많은 서비스들은 제공되는 Paas Saas 와 같은 Cloud platform을 활용하여 시스템 운용 비용을 낮추고 알람, 분산 처리, 스토리지 서버 등 여러가지를 aws를 통해 구성하게 됩니다.
- 물론 GCP, Azure, NCP, Oracle cloud 같은 것도 존재하지만 aws가 제일 무난한 선택이라고 생각이 듭니다.

<br/>

### **etc : Git, Github**
- git을 통한 버전 관리 개념은 프로젝트를 진행하기 위한 정말 기본적인 소양입니다. (기본이라고 엄청 쉽다! 이런건 아닙니다.. 저는 개인적으로 언어 공부할 때보다 어려웠거든요.) 뭐.. 혼자 취업을 준비하시는 분들은 이부분을 간과하시는 경우가 많은데요. 사실 면접때 물어보진 않고 온보딩때 알려주시기도 합니다.
- 서론이 길었는데요. ㅎㅎ git을 사용하여 협업을 진행하는 git-flow 와 같은 것을 미리 숙지하시고, github을 통해 진행해왔던 프로젝트를 관리하고 꾸며놓는 것은 정말 좋은 방법이라고 생각합니다.
- https://backlog.com/git-tutorial/kr/stepup/stepup1_1.html
- https://www.inflearn.com/course/git-and-github
- https://www.inflearn.com/course/%EB%B9%A0%EB%A5%B4%EA%B2%8C-git
- https://www.inflearn.com/course/git-%EA%B0%95%EC%A2%8C-%EC%83%9D%ED%99%9C%EC%BD%94%EB%94%A9
- https://brunch.co.kr/@fermat39/84

<br/>

### **etc : 인프라 보충 학습** 

- [서적 : 그림으로 공부하는 IT 인프라 구조](http://www.yes24.com/Product/Goods/95800974)
- [서적 : 그림으로 공부하는 시스템 성능 구조](http://www.yes24.com/Product/Goods/17947564?OzSrank=1)
- 제가 개인적으로 좋아하는 그림으로 배우는 시리즈의 인프라 관련 서적입니다. 인프라 서버 구조와 성능 지표, 개선 등에 대한 내용을 공부할 수 있습니다.

<br/>

### **개인 프로젝트 진행**

- 앞에서 경험했던 기술들을 본인만의 요구 사항에 녹이고 적용하여 프로젝트를 진행하시면 좋을 것 같습니다.
- 모든 방식에는 장단점이 존재하기 때문에. 이를 비교하고 설명할 수 있어야한다고 생각합니다. (물론 저는 못합니다..)
    - ex) 객체 간의 변환 시에 MapStruct를 사용하셨는데 메서드를 통해 작성하는 방법이나 ModelMapper를 사용하는 방식도 있지 않나요? 왜 MapStruct를 사용하셨는지 설명해주실 수 있으실까요? 등..
    - 사실 라이브러리에 특정되는 질문은 잘 하지 않습니다. RabbitMQ, Redis, No-SQL, SQL 등 상황에 따라 여러 가지를 고려하고 도입한 이유가 더 중요합니다.


<br/>

## **이후는 따로 서술된 항목이나 주변의 추천을 통해 추가 학습 진행**
- 이 문서에 정리된 자바, 스프링, SQL 등 정리된 항목의 좀 더 심화적인 책을 학습하고 차근차근 개념을 정리하는 것을 추천합니다.
- 면접 질문 리스트는 신입 ~ 주니어 (2년차 정도) 수준까지 예상을 하여 작성한 것이기에 쉬운 질문부터 정리해보는 것을 추천합니다.

<br/>

### Spring Security 학습 추천 방식
- Spring에서 제공하는 인증 및 인가를 담당하는 모듈입니다. 직접 인증 및 인가 기능을 구현하는 것보다는 이미 구현된 모듈을 통해 여러 기능을 제공하고 취약한 부분을 보완하는 것이 더 경제적이기 때문에 Spring Security는 많이 사용됩니다.
- 이론 학습 위주의 경우 : Java의 Thread Local, Proxy, Web 생태계의 HttpSession, Cookie, WAS의 JSESSIONID, Servlet의 Filter 그리고 인증과 인가의 개념을 학습하신 뒤 보는 것을 추천합니다(이 개념들을 기반으로 많은 기능들이 구현되어 있습니다.)
- 프로젝트 기반 학습의 경우 : 이 경우에는 HttpSession과 AOP를 이용하여 인증 및 인가 처리를 구현해보신 다음 Security로 고도화하는 경험을 해보는 것도 좋다고 생각합니다.

<br/>

### 좀 더 넓혀가기

- 도메인 주도 설계 핵심, 도메인 주도 설계
- Message broker, RabbitMQ
- Nginx
- Kotlin
- Javascript and Library (Node.js Runtime, express, nest, React or Vue..)

<br/>

### 좀 더 나아가기

- Effective SQL -> Real MySQL 8.0
- 데이터 중심 애플리케이션 설계
- 가상 면접 사례로 배우는 대규모 시스템 설계 기초
       
<br/>

---

<br/>

# 프로젝트

## Sample Projects 
프로젝트 중 도입을 위해 학습하실 때 참고하실 수 있도록 만들어본 Project들 입니다. (저도 학습해서 정리하고 있습니다.)
### https://github.com/Lob-dev/Sample-Cache

- Spring Data Redis, Cachemanager, Annotations..
- 학습 및 Sample 용으로 만들었기 때문에 도입할 필요 없는 리소스에 캐싱을 설정하였습니다.

<br/>

### https://github.com/Lob-dev/Sample-Auth

- Spring Security, Oauth2, JWT(Sessionless), ExceptionAdvice, logging
- 현재 유지 단계인 Security Oauth2 JWT 라이브러리를 사용하였습니다.
- 새로 개발된 모듈의 레퍼런스가 충분해진다면 마이그레이션을 진행할 예정입니다.

<br/>

### https://github.com/Lob-dev/Sample-prometheus

- Spring Web, Actuator, RabbitMQ, Prometheus, grafana
- 각 Application의 metric 정보를 수집하여 모니터링할 수 있도록 구현되어 있습니다.

<br/>

## 참고

[공공데이터 포털](https://www.data.go.kr/)

[public apis - 영어](https://github.com/public-apis/public-apis)

[API란? 개념 정리와 포트폴리오에 유용한 대박 사이트 공유 🙌 Youtube](https://www.youtube.com/watch?v=ogT267HvNuQ&t=337s&ab_channel=%EB%93%9C%EB%A6%BC%EC%BD%94%EB%94%A9by%EC%97%98%EB%A6%AC)

---
