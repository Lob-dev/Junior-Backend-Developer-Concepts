
# 개인적으로 추천하는 입문 학습 흐름

## 자바 입문부터 스프링를 활용한 첫 토이 프로젝트까지

<br/>

### **자바 기본서 항목 1독**

- [https://lob-dev.tistory.com/entry/Java의-Reflection-API](https://lob-dev.tistory.com/entry/Java%EC%9D%98-Reflection-API)

<br/>

### **객체 지향의 사실과 오해**

<br/>

### **SQL 첫걸음 혹은 기타 SQL 책**

- CRUD, Local or Global transaction, DDL 기본 , Index
- 대부분의 서비스는 CRUD를 무조건적으로 포함한다고 봐야됩니다. 이는 게시판 같은 것에 특정 되는 개념이 아니라 모든 데이터를 다룸에 있어서 통용되는 것입니다.
- 트랜잭션, 인덱스 개념은 개발자에겐 필수 개념이라고 생각합니다.

<br/>

### **Sevlet API (JSP는 제외)**

- Server - Client Model, HTTP, SSR and CSR, JSON, RESTful API*
- Servlet은 자바 기반의 "표준" Protocol API이며, HTTP와 기타 Protocol을 처리하는 뼈대가 됩니다. 스프링이나 Vaddin, Struct 같은 프레임워크도 내부적으로는 Servlet을 통해 동작하는 기능들이 있습니다. 자바 기반의 웹 근본 개념 이해를 위해 우선하여 학습하는 것을 추천합니다.
- [https://lob-dev.tistory.com/entry/CGI-Servlet-Servlet-Container](https://lob-dev.tistory.com/entry/CGI-Servlet-Servlet-Container)
- [https://lob-dev.tistory.com/entry/01-RESTful-개념과-사전-지식](https://lob-dev.tistory.com/entry/01-RESTful-%EA%B0%9C%EB%85%90%EA%B3%BC-%EC%82%AC%EC%A0%84-%EC%A7%80%EC%8B%9D)

<br/>

### **JDBC API**

- JDBC는 자바 기반의 "표준" DB 접근 API이며, Mybatis, JPA 와 같은 SQL Mapper, ORM 프레임워크들도 내부적으로는 JDBC의 Connection과 Statement를 사용하기 때문에 이를 통한 애플리케이션 시점에서의 로컬, 글로벌 트랜잭션 방식을 이해하는 것이 개인적으로 중요하다고 생각합니다.
- [https://lob-dev.tistory.com/entry/Java-Database-Connectivity-알아보기](https://lob-dev.tistory.com/entry/Java-Database-Connectivity-%EC%95%8C%EC%95%84%EB%B3%B4%EA%B8%B0)

<br/>

### **스프링 입문을 위한 자바 객체 지향의 원리와 이해**

- Spring을 학습하기 이전에 JVM의 메모리, 객체 지향 개념과 구현 방식을 다시 복습할 수 있고, Spring에 적용된 디자인 패턴을 선행 학습할 수 있는 좋은 책입니다.
- [https://lob-dev.tistory.com/entry/책임을-중시하는-객체-지향-디자인의-핵심-개념-GRASP](https://lob-dev.tistory.com/entry/%EC%B1%85%EC%9E%84%EC%9D%84-%EC%A4%91%EC%8B%9C%ED%95%98%EB%8A%94-%EA%B0%9D%EC%B2%B4-%EC%A7%80%ED%96%A5-%EB%94%94%EC%9E%90%EC%9D%B8%EC%9D%98-%ED%95%B5%EC%8B%AC-%EA%B0%9C%EB%85%90-GRASP)

<br/>

### **코드로 배우는 스프링 부트 웹 프로젝트**

- 취업이나 상황에 따라 시간이 부족하다면 앞선 책을 건너뛰고 해당 책으로 학습을 하는 것도 추천하기도 합니다. 입문 서적으로는 좋은 책인 것 같습니다.

<br/>

### **인프런 스프링 입문 - 코드로 배우는 스프링 부트, 웹 MVC, DB 접근 기술**

- 기본적인 Spring Boot 애플리케이션을 경험해볼 수 있는 좋은 입문 강의입니다. MVC 요청 흐름과 템플릿 엔진 등의 개념을 경험해볼 수 있습니다.

<br/>

### **처음 배우는 스프링 부트 2 (Optional)**

- Spring Boot 모듈의 의존성 관리, 자동 설정. 테스트 환경 등을 설명하며 게시판 예제를 통해 Oauth2, Security, RESTful, Batch 등의 기본적인 개념과 예제를 다룹니다.

<br/>

### **etc : docker 학습**

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

### **etc : aws, cloud 기본 학습**

- https://www.inflearn.com/course/aws-%ED%81%B4%EB%9D%BC%EC%9A%B0%EB%93%9C-%EC%8B%9C%EC%9E%91%ED%95%98%EA%B8%B0#curriculum 혹은 기타 링크
- http://www.yes24.com/Product/Goods/102368122?OzSrank=4 , http://www.yes24.com/Product/Goods/73363873?OzSrank=21 혹은 기타 서적
- 최근 많은 서비스들은 제공되는 Paas Saas 와 같은 Cloud platform을 활용하여 시스템 운용 비용을 낮추고 알람, 분산 처리, 스토리지 서버 등 여러가지를 aws를 통해 구성하게 됩니다.
- 물론 GCP, Azure, NCP, Oracle cloud 같은 것도 존재하지만 aws가 제일 무난한 선택이라고 생각이 듭니다.

<br/>

### **etc : git, github**
- git을 통한 버전 관리 개념은 프로젝트를 진행하기 위한 정말 기본적인 소양입니다. (기본이라고 엄청 쉽다! 이런건 아닙니다.. 저는 개인적으로 언어 공부할 때보다 어려웠거든요.) 뭐.. 혼자 취업을 준비하시는 분들은 이부분을 간과하시는 경우가 많은데요. 사실 면접때 물어보진 않고 온보딩때 알려주시기도 합니다.
- 서론이 길었는데요. ㅎㅎ git을 사용하여 협업을 진행하는 git-flow 와 같은 것을 미리 숙지하시고, github을 통해 진행해왔던 프로젝트를 관리하고 꾸며놓는 것은 정말 좋은 방법이라고 생각합니다.
- https://backlog.com/git-tutorial/kr/stepup/stepup1_1.html
- https://www.inflearn.com/course/git-and-github
- https://www.inflearn.com/course/%EB%B9%A0%EB%A5%B4%EA%B2%8C-git
- https://www.inflearn.com/course/git-%EA%B0%95%EC%A2%8C-%EC%83%9D%ED%99%9C%EC%BD%94%EB%94%A9
- https://brunch.co.kr/@fermat39/84

<br/>

### **개인 프로젝트 진행**

- 앞에서 경험했던 기술들을 본인만의 요구 사항에 녹이고 적용하여 프로젝트를 진행하시면 좋을 것 같습니다.
- 모든 방식에는 장단점이 존재하기 때문에. 이를 비교하고 설명할 수 있어야한다고 생각합니다. (물론 저는 못합니다..)
    - ex) 객체 간의 변환 시에 MapStruct를 사용하셨는데 메서드를 통해 작성하는 방법이나 ModelMapper를 사용하는 방식도 있지 않나요? 왜 MapStruct를 사용하셨는지 설명해주실 수 있으실까요? 등..
    - 사실 라이브러리에 특정되는 질문은 잘 하지 않습니다. RabbitMQ, Redis, No-SQL, SQL 등 상황에 따라 여러 가지를 고려하고 도입한 이유가 더 중요합니다.


<br/>

**이후는 위에 따로 서술된 항목이나 주변의 추천을 통해 추가 학습 진행**

<br/>

---

<br/>

# 프로젝트

## Sample Projects 
학습하실 때 참고하실 수 있도록 만들어본 Project들 입니다.
### https://github.com/Lob-dev/Sample-Cache

- Spring Data Redis, Cachemanager, Annotations..
- 학습 및 Sample 용으로 만들었기 때문에 도입할 필요 없는 리소스에 캐싱을 설정하였습니다.

<br/>

### https://github.com/Lob-dev/Sample-Auth

- Spring Security, Oauth2, JWT(Sessionless), ExceptionAdvice, logging
- 현재 유지 단계인 Security Oauth2 JWT 라이브러리를 사용하였습니다.
- 새로 개발된 모듈의 레퍼런스가 충분해진다면 마이그레이션을 진행할 예정입니다.

<br/>

## 참고

[공공데이터 포털](https://www.data.go.kr/)

[public apis - 영어](https://github.com/public-apis/public-apis)

[API란? 개념 정리와 포트폴리오에 유용한 대박 사이트 공유 🙌 Youtube](https://www.youtube.com/watch?v=ogT267HvNuQ&t=337s&ab_channel=%EB%93%9C%EB%A6%BC%EC%BD%94%EB%94%A9by%EC%97%98%EB%A6%AC)

---
