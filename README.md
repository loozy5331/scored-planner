# scored-planner
점수 계획표 프로젝트 (version 2)

## 목표
1. 긴 간격을 가지고 반복되는 계획들 확인
2. 계획 수행 후 평가(점수)

## TODO
1. 아키텍처 변경
  - docker-compose -> k8s + helm
  - 배포는 AWS EKS 사용
  - DB는 MySQL을 활용해보기
    - 가용성 확보를 위한 작업 수행(공부 필요)
2. 애플리케이션 서비스
  - 카카오톡을 통한 일정 공유
  - 범용 로그인(ex. google, kakao 등) 구현
  - UI 개선
3. CI/CD 서비스 구축
  - CI - ArgoWorkflow
  - CD - ArgoCD
4. 로깅 서비스 구축
  - EFK 사용 (ElasticSearch, Fluent-bit, Kibana)
5. 모니터링 서비스 구축 
  - prometheus & grafana
6. 서비스 분석을 위한 환경 구축 (공부 필요)
  - 배치 - hadoop's hdfs
  - 실시간 - kafka
