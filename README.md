# aws-practice


## 1. S3 - Simple Storage Service

> 1-1. 객체를 저장하는 스토리지
>
> 1-2. HTTP 또는 HTTPS를 사용하여 웹 어디서든 데이터를 저장 및 검색
>
> 1-3. 데이터를 자주 읽어들임


## 2. IAM - Identity & Access Management

> 2-1. 보안 서비스


## 3. WAF - Web Application Firewall


## 4. Shield

> 4-1. DDoS(분산 서비스 거부) 공격으로부터 방어


## 5. CloudTrail

> 5-1. 계정에 대한 모든 AWS API를 관리해주는 서비스


## 6. Config

> 6-1. AWS 인벤토리 및 구성을 추적하고 구성 변경 알림을 제공하는 관리형 서비스
>
> 6-2. 규정 준수 감사, 변경 관리, 문제 해결 등


## 7. CloudFormation

> 7-1. 개발자 에러가 많이 없어진다.
>
> 7-2. 고객사에서 데모나 표시를 할 때 이 서비스만 가져가서 실행만 해도 가능하다.


## 8. Marketplace

> 8-1. 4,200개의 소프트웨어 목록
> 
> 8-2. AWS에 없는 서비스를 받아올 수 있다.


## 9. VPC - Virtual Private Cloud

> 9-1. AWS 클라우드 내 격리된 가상 서브넷
>
> 9-2. 강력한 보안을 지원
>
> 9-3. 네트워크를 분리할 수 있다.
>
> 9-4. 사용자 정의 IP 주소 범위, 서브넷, 라우팅 테이블, 액세스 제어 목록, 네트워크 게이트웨이만 있으면 구축 가능
>
> 9-5. 속도, 큰 데이터 -> Direct Connect와 고려해봐야 한다.


## 10. ELB - Elastic Load Balancer

> 10-1. Application Load Balancer
>
> 10-2. Network Load Balancer
> - 고정 IP를 사용할 수 있음


## 11. CloudFront


## 12. Route 53

> 12-1. root 계층까지의 dns 서버
>
> 12-2. region간 failover를 할 수 있다.


## 13. RDS - Relational Database Service

> 13-1. 작업, 패치 관리, 복제 등 시간 소모적인 데이터베이스의 작업을 처리
>
> 13-2. root 계정은 사용할 수 없고, 권한을 부여받아 사용할 수 있다.


## 14. 요약

> 14-1. 이중화 구성을 하여 장애 발생 시 Single point를 무시할 수 있어야 한다.
>
> 14-2. Direct connect - LG U+
>
> 14-3. Security Group, NACL - 보안
>
> 14-4. S3, Shield, IAM 등은 VPC 외부에 존재함.
>
> 14-5. Inspector - EC2 OS의 취약점을 보완해줌.
>
> 14-6. Certification Manager - SSL/TLS 인증서
>
> 14-7. Macie - 민감한 데이터 검색 및 분류
>
> 14-8. AWS - 리소스 구성 측정, 감사, 평가


## 15. 스토리지 옵션

> 15-1. EBS, S3, RDS, DynamoDB ...
>
> 15-2. S3 - Object Storage
>
> 15-3. S3 대신 Cloud Front를 이용하면 빠를 수 있다.
>
> 15-4. 세밀한 쿼리 - RDS / 반대 - DynamoDB(NoSQL)
>
> 15-5. AutoScaling을 사용해서 최대한 자원의 손실을 방지한다.
>
> 15-6. 탄력적인 운영


## 16. Loose-coupling

> 16-1. 안정적인 처리
>
> 16-2. 하나만 오류가 발생해도 실행되지 않음
>
> 16-3. <-> Tight-coupling 오류가 발생해도 빠르게 실행됨


