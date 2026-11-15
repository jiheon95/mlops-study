# MLOps Study

가시다 MLOps 스터디 정리 저장소

## 목차

| 챕터 | 주제 | 상태 |
|---|---|---|
| [CH1](docs/ch01.md) | MLOps와 ML 엔지니어링 시작 | 완료 |
| [CH2](docs/ch02.md) | MLOps란 무엇인가 | 완료 |
| [CH3](docs/ch03.md) | 쿠버네티스 기초 | 요약 |
| [CH4](docs/ch04.md) | 신뢰할 수 있는 ML 시스템 설계 (MLflow, Feast) | 완료 |
| [CH5](docs/ch05.md) | ML 파이프라인 오케스트레이션 (Kubeflow Pipelines) | 완료 |
| [CH6](docs/ch06.md) | ML 모델 프로덕션화 (BentoML, Evidently) | 완료 |
| [CH7](docs/ch07.md) | 데이터 분석과 준비 (Kubeflow Notebooks, KFP 데이터 전달) | 진행 중 (7.2.1까지) |
| [CH8](docs/ch08.md) | 노드 기능 선택과 파드 배치 (어피니티, 테인트/톨러레이션, 토폴로지 분산) | 완료 |
| [CH9](docs/ch09.md) | 스테이트풀 애플리케이션 (볼륨, PV/PVC, StorageClass, StatefulSet) | 완료 |

## 책에서 쓰는 스택

| 역할 | 도구 |
|---|---|
| 플랫폼 | Kubernetes, Kubeflow |
| 파이프라인 오케스트레이션 | Kubeflow Pipelines |
| 피처 스토어 | Feast |
| 실험 추적 · 모델 레지스트리 | MLflow |
| 서빙 · 배포 | BentoML, Yatai, Chainlit, Docker, CI/CD |
| 모니터링 · 드리프트 | Prometheus, Evidently, Langfuse |
| 애노테이션 | CVAT |
