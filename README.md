프로젝트 스펙
1. 컨텐츠??
이벤트소싱 CQRS

2. CRUD 기능

3. RESTFul API 

4. Kubernetes - docker

5. kafka (message queue)

6. ElasticSearch


MSA를 위한 사전 스터디 프로젝트 설계
1. MSA 의 장애 대처 능력을 향상 시켜야 한다ㅣ
 - 이벤트 소싱 패턴을 이용하여 각 Action 대한 처리


이벤트 소싱 적용
1. 조회는 어떻게??
 - CQRS 를 통해서 R과 CUD를 구분하자
 - 스냅샷을 통해서 조회의 속도를 개선하자
2. 중복 액션에 대한 처리는 어떻게 할 것인가?
 - ???
3. 이벤트 소싱을 어떻게 처리할 것인가??
 - 카프카를 통하여 메세지를 쌓고 처리가 완료되면 Sync를 맞춰준다. (분산의 용이성도 갖출 수 있다)
 
부하 테스트 및 유닛 테스트 모델
1. RESTful API 과 GraphQL 을 제공
 - client에서 반복 호출 (테스트 모듈이 될수도)
 
배포 방법
1. kubernetes, docker


어떤 컨텐츠로 만들 것인가?? 요것이 문제로다
