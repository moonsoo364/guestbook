## 젠킨스를 이용한 CI/CD 테스트용 Repository
- webhook 설정으로 git에 코드가 push 되면 젠킨스에서 빌드 자동화 가능
- 젠킨스의 Junit 플러그인으로 테스트 코드를 실행하고 메일 알림 가능
- 젠킨스 Agent로 도커 컨테이너를 실행하는 Host와 Junit을 실행하는 Host를 구분해서 PipeLine 구성 가능 
