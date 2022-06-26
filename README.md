# healthier : django-vote-15th
15기 Frontend, Backend 파트장 투표 어플리케이션입니다  

## ✔️ 당신이 원하는 파트장에게 투표하세요 ✔️

### 특별한 점
1. 본인이 원하는 후보를 ❗**1명씩**❗ 투표할 수 있습니다
2. 본인이 원하는 후보를 ❗**여러 번**❗ 투표할 수 있습니다 
3. ❗**다중 투표**❗가 가능합니다

## ERD
![erd](https://user-images.githubusercontent.com/77188666/175807082-ccd0b6b3-a95b-4102-8b5b-84ecc73d71a6.PNG)

## API 문서
[📕 Notion](https://yourzinc.notion.site/django-vote-15th-API-74b44c1773b44e1d9dd7c043e514a0b8)

[📘 Postman](https://documenter.getpostman.com/view/20851554/UzBqpkpp)

---

### - Docker와 Github Action을 이용한 자동 배포 
### - AbstractUser 을 이용하여 User Model을 Custom
### - Simple JWT을 이용하여 회원가입/로그인
### - permissions_class로 로그인 인증 후 투표

---

### ❗ 어려웠던 점 ❗

- [x] ubuntu 에서 python 설치 및 module 버전 호환 문제
- [ ] aws EC2의 public IPv4 접속이 안되는 문제 
- [ ] http -> https 배포 문제 (A 레코드 생성 X)

---

### ❗ Refactoring이 필요한 부분 ❗

- [ ] logout 기능
- [ ] 투표 log 생성
- [ ] https 배포
