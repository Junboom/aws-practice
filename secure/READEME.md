# secure

## 1. 웹 방화벽

> 1-1. CDN 유형: 인터넷과 노출됨이 없이 사용할 수 있다.


## 2. AWF

> 2-1. SQL Injection : 웹에 노출된 경우가 있었음.
>
> 2-2. 구현이 쉽지 않다.
>
> 2-3. CloudFlare, SOPHOS, F5 etc..
>
> 2-4. Marketplace의 WAF는 EC2에 올라가 있다.


## 3. DDoS 트랜드

> 3-1. DDoS 공격은 UDP로 공격하는 경우가 많다.
>
> 3-2. CloudFront가 1차적으로 트래픽을 받고 Customer Solution으로 넘긴다.


## 4. API Gateway

> 4-1. EC2가 장애날 경우
>
> 4-2. 일반적인 DDoS 방어가 된다.


## 5. 권장 아키텍처

> 5-1. 1차적으로 S3, CloudFront가 받는다.


