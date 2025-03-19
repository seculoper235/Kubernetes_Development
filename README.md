# Kubernetes Development
---
## 개요
- Kubernetes로 다양한 인프라 모델을 구축해보기 위한 저장소입니다
- 다음의 2가지 책과 공식 홈페이지를 참조하며 정리하였습니다
  - 쿠버네티스 교과서
  - 컨테이너 인프라 환경 구축을 위한 쿠버네티스/도커
  - 공식 홈페이지(https://kubernetes.io/ko/)

---
## 🌟 관련 서비스
* 웹 서비스(Frontend) - [https://github.com/seculoper235/infra-test-web](https://github.com/seculoper235/infra-test-web)

* 투두 리스트 서비스 - [https://github.com/seculoper235/infra-test-api](https://github.com/seculoper235/infra-test-api)

* 포스트 서비스 - [https://github.com/seculoper235/infra-post-service](https://github.com/seculoper235/infra-post-service)

* 파일 서비스 - [https://github.com/seculoper235/infra-file-service](https://github.com/seculoper235/infra-file-service)

---
## 📝 관련 작성글

### 🍀 도커
* [Docker 란?](https://velog.io/@seculoper235/Docker-%EB%9E%80)

* [DockerFile에 대해](https://velog.io/@seculoper235/DockerFile)

* [Docker의 Layer와 Volume?](https://velog.io/@seculoper235/Docker-Layer%EC%97%90-%EB%8C%80%ED%95%B4)
</br>

### 🍀 쿠버네티스
* [Kubernetes 사용환경 정리?](https://velog.io/@seculoper235/Kubernetes-%EC%82%AC%EC%9A%A9-%EB%8F%84%EA%B5%AC-%EC%A0%95%EB%A6%AC%EC%9E%91%EC%84%B1%EC%A4%91)

* [Kubernetes 구성요소](https://velog.io/@seculoper235/Kubernetes-%EA%B5%AC%EC%84%B1-%EC%9A%94%EC%86%8C%EC%9E%91%EC%84%B1%EC%A4%91)

* [Service 란?](https://velog.io/@seculoper235/Kubernetes-Service-%EC%98%A4%EB%B8%8C%EC%A0%9D%ED%8A%B8%EB%9E%80)

* [ConfigMap과 Secret 이란?](https://velog.io/@seculoper235/Kubernetes-ConfigMap%EA%B3%BC-Secret)

* [Volume 이란?](https://velog.io/@seculoper235/Kubernetes-Volume-%EC%9D%B4%EB%9E%80)

* [PV, PVC에 대해](https://velog.io/@seculoper235/Kubernetes-PV-PVC-%EB%B6%84%EB%A5%98)

* [StorageClass와 동적 프로비저닝](https://velog.io/@seculoper235/Kubernetes-PV-PVC-%EB%B6%84%EB%A5%98)

* [데몬셋 이란?](https://velog.io/@seculoper235/Kubernetes-DeamonSet-%EC%9D%B4%EB%9E%80)
</br>

### 🍀 ELK Stack
* [분산 처리 시스템이란?](https://velog.io/@seculoper235/%EA%B3%A0%EC%B0%B0-%EB%B6%84%EC%82%B0-%EC%B2%98%EB%A6%AC-%EC%8B%9C%EC%8A%A4%ED%85%9C%EC%9D%B4%EB%9E%80)
  
* [로그 관리를 해보자 - 로깅 전략 분석](https://velog.io/@seculoper235/Kubernetes-%EB%A1%9C%EA%B7%B8-%EA%B4%80%EB%A6%AC%EB%A5%BC-%ED%95%B4%EB%B3%B4%EC%9E%90-1%ED%8E%B8)

* [로그 관리를 해보자 - LogStash 란?](https://velog.io/@seculoper235/Kubernetes-%EB%A1%9C%EA%B7%B8-%EA%B4%80%EB%A6%AC%EB%A5%BC-%ED%95%B4%EB%B3%B4%EC%9E%90-ELK-%EB%9E%80%EC%9E%91%EC%84%B1%EC%A4%91)

* [로그 관리를 해보자 - ElasticSearch 란?](https://velog.io/@seculoper235/ELK-%EB%A1%9C%EA%B7%B8-%EA%B4%80%EB%A6%AC%EB%A5%BC-%ED%95%B4%EB%B3%B4%EC%9E%90-ElasticSearch-%EB%9E%80%EC%9E%91%EC%84%B1%EC%A4%91)


---
## 😁 As-Is
* 단일 노드 쿠버네티스 서비스 구축하기([관련 설정 참조](infra/description.md))

* 로깅 시스템 구축하기([관련 설정 참조](infra/logging/description.md))
  
* 2개 이상의 API 서비스를 제공하는 서비스(MSA) 구축하기(해당 문서의 [관련 서비스](https://github.com/seculoper235/Kubernetes_Development/tree/master?tab=readme-ov-file#-%EA%B4%80%EB%A0%A8-%EC%84%9C%EB%B9%84%EC%8A%A4) 참조)
---
## 💡 To-Be
* 인증 API 서비스 및 API Gateway 구축하기
