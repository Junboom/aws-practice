# simple-script

## 1. ls al > lists

-> lists에 ls al 정보가 저장된다.


## 2. sudo vi script

\#!/bin/bash

lists = `cat /ect/passwd`

for USER in $lists; do

echo $USER | grep ec2-user

done


## 3. 실행 권한 부여

sudo shmod 755 ___


## 4. AWS 접근

aws ec2 describe-regions --region ap-northeast-2 --output text | grep ap-northeast-2 | owk "{print$3}"


## 5. grep으로 횡에서 특정 데이터를 뽑는다.


## 6. 업무

\#!/bin/bash

lists = `aws ec2 describe-regions --region ap-northeast-2 --output text`

for USER in $lists; do

echo "=========="; ₩

echo -e "₩Welcome: '$USER'";

aws ec2 describe-vpcs --region $USER --output text;

echo "=========="; ₩

done


## 7. ip 주소 확인하기

nslookup ELB.com


## 8. aws 활용하기

> 8-1. aws iam list-users --query Users[].UserName
>
> 8-2. aws ec2 descrive-instances --query "Reservations[].Instances[].[InstanceId, State.Name, Tags[?Key=='Name'] | [0].Value]"
> output 설정: --output json/text/table



