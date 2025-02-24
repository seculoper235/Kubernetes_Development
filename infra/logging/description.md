Logging System
---
## 개요
**ECK를 활용하여 Elastic Stack으로 구현**된 로깅 시스템이다\
스택은 다음과 같다

| 데이터 수집   | 데이터 가공   | 분산 처리 시스템     | 시각화 및 관리 |
|----------|----------|---------------|----------|
| Filebeat | Logstash | ElasticSearch | Kibana   |

---
## 📝 로깅 시스템 배포
다음 순서대로 배포를 진행한다

### ElasticSearch 배포
```shell
kubectl -f infra/logging/elasticsearch.yaml
```
---

### Logstash, Filebeat 배포
```shell
kubectl -f infra/logging/logstash.yaml
kubectl -f infra/logging/front-filebeat.yaml -f infra/logging/back-filebeat.yaml
```
---

### Kibana 배포
```shell
kubectl -f infra/logging/kibana.yaml
```
---