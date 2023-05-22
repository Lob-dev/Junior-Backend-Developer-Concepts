<p align="center">
  <img src="https://user-images.githubusercontent.com/67903919/147674116-80149e7b-75ce-4c1f-8c96-e6addb0eed08.png">
</p>

<br/>
<br/>

## **개인 프로젝트 진행**

- 앞에서 경험했던 기술들을 본인만의 요구 사항에 녹이고 적용하여 프로젝트를 진행하시면 좋을 것 같습니다.
- 모든 방식에는 장단점이 존재하기 때문에. 이를 비교하고 설명할 수 있어야한다고 생각합니다. (물론 저는 못합니다..)
    - ex) 객체 간의 변환 시에 MapStruct를 사용하셨는데 메서드를 통해 작성하는 방법이나 ModelMapper를 사용하는 방식도 있지 않나요? 왜 MapStruct를 사용하셨는지 설명해주실 수 있으실까요? 등..
    - 사실 라이브러리에 특정되는 질문은 잘 하지 않습니다. RabbitMQ, Redis, No-SQL, SQL 등 상황에 따라 여러 가지를 고려하고 도입한 이유가 더 중요합니다.
    - 이력서에서 프로젝트에 대한 내용을 작성하실 때에는 본인 만의 요구사항을 위주로 이를 구현한 방법, 어떻게 고려하였는지, 문제가 발생했다면 어떻게 해결하였는지를 요약해서 나열하는 것이 어필하기 좋다고 생각합니다. (저도 처음부터 이렇게 했었으면 더 좋았을 탠데요.. ㅎㅎ;) 
    - 단순 기술 스택의 나열이나 당연한 이야기들 (DB 연동을 통해 사용자 데이터 영속화 처리를 하였다.. 라던지)을 넣는 것은 그렇게 도움이 되지 않습니다.

<br/>

## **이후 따로 서술된 항목이나 주변의 추천을 통해 심화 및 추가 학습 진행**
- 이 문서에 정리된 자바, 스프링, SQL 등 정리된 항목의 좀 더 심화적인 책을 학습하고 차근차근 개념을 정리하는 것을 추천합니다.
- 면접 질문 리스트는 신입 ~ 주니어 (2년차 정도) 수준까지 예상을 하여 작성한 것이기에 쉬운 질문부터 정리해보는 것을 추천합니다.

<br/>

### **Spring Security 학습 추천 방식**
- Spring에서 제공하는 인증 및 인가를 담당하는 모듈입니다. 직접 인증 및 인가 기능을 구현하는 것보다는 이미 구현된 모듈을 통해 여러 기능을 제공하고 취약한 부분을 보완하는 것이 더 경제적이기 때문에 Spring Security는 많이 사용됩니다.
- 이론 학습 위주의 경우 : Java의 Thread Local, Proxy, HttpSession, Cookie, WAS의 JSESSIONID, Servlet의 Filter, Chaining 그리고 인증과 인가의 개념을 학습하신 뒤 보는 것을 추천합니다. (이 개념들을 기반으로 많은 기능들이 구현되어 있습니다.)
- 프로젝트 기반 학습의 경우 : 이 경우에는 HttpSession과 AOP를 이용하여 인증 및 인가 처리를 구현해보신 다음 Security로 고도화하는 경험을 해보는 것도 좋다고 생각합니다.

<br/>

### **이후에 학습해야 할 것들**

- DDD (도메인 주도 설계) : 도메인 주도 설계 철저 입문, 도메인 주도 설계 핵심, 도메인 주도 설계, 도메인 주도 설계 구현 등
- Message broker or Message Queue : ActiveMQ, RabbitMQ, Kafka, Amazon SQS 등
- Web Server or Reverse Proxy : Apache, Nginx 등
- Middleware : HaProxy, ProxySQL 등
- HA, Failover : Redis Sentinel & Cluster, Galera Cluster, Active-standby, Replication, Micro Service 등
- Javascript and Library : Node.js Runtime, express, Nest 등
- Front : React, Svelt, Vue 등
- CI / CD : Jenkins, Gitlab-Ci, Github Action, Argocd 등
- Container Orchestration : Kubernetes 등
- Test : Unit test, Integration test, mock test, TDD, ATDD, Test tools (Ngrinder, K6, Artillery, Jmeter 사용법 등)
- Etc : Kotlin, Go 등
       
<br/>

---

<br/>

## **Sample Projects**
제 개인적으로 PoC 또는 학습 용도로 만들고 있는 Project Repo 입니다.
### https://github.com/Lob-dev/The-Joy-Of-Java

<br/>

## 참고

### **[공공데이터 포털](https://www.data.go.kr/)**

### **[public apis - 영어](https://github.com/public-apis/public-apis)**

### **[API란? 개념 정리와 포트폴리오에 유용한 대박 사이트 공유 🙌 Youtube](https://www.youtube.com/watch?v=ogT267HvNuQ&t=337s&ab_channel=%EB%93%9C%EB%A6%BC%EC%BD%94%EB%94%A9by%EC%97%98%EB%A6%AC)**

---
