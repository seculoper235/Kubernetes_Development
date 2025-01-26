# Single Node Cluster Infra Service
---
## 개요
- todo-list 기능을 가진 웹 서비스이다
- **단일 노드 클러스터 환경(로컬)**의 쿠버네티스 서비스이다
- 다음의 3가지가 준비되어 있어야 한다
    - infra-frontend 이미지
    - infra-backend 이미지
    - 별도의 DB 서버

---
## 📝 infra-frontend Image
다음 git 저장소의 README.md 참고\
**https://github.com/seculoper235/infra-test-web**

---
## 📝 infra-backend Image / DB 서버
다음 git 저장소의 README.md 참고\
**https://github.com/seculoper235/infra-test-api**
---

## 📝 쿠버네티스 배포
다음 순서대로 배포를 진행한다

### Secret, db-service 배포
```shell
kubectl -f infra/secret/infra-secret.yaml -f infra/database/db-service.yaml
```
---

### Deployment 배포
```shell
kubectl -f infra/backend/infra-backend.yaml -f infra/frontend/infra-frontend.yaml
```
---

### Service 배포
```shell
kubectl -f infra/backend/backend-service.yaml -f infra/frontend/frontend-service.yaml
```
---