
# 개인적으로 추천하는 백엔드 입문 학습 흐름

## 자바 입문부터 스프링 프레임워크를 이용한 첫 프로젝트 개발까지

<p align="center">
  <img src="https://user-images.githubusercontent.com/67903919/147674116-80149e7b-75ce-4c1f-8c96-e6addb0eed08.png">
</p>

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
