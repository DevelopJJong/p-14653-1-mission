# p-14653-1-mission
# 1부: Kubernetes 환경 구축
## 0001 완료
### - Kubernetes 환경 구축
## 0002 완료
### - kubectl 기본 명령어
# 2부: Pod 기초
## 0003 완료
### - 첫 번째 Pod 생성하기
## 0004 완료
### - YAML 파일로 Pod 정의하기
## 0005 완료
### - Multi-Container Pod
# 3부: Deployment와 ReplicaSet
## 0006 완료
### - Deployment 생성하기
## 0007 완료
### - 스케일링 (Scaling)
## 0008 완료
### - 롤링 업데이트 (Rolling Update)
# 4부: Service
## 0009 완료
### - Cluster IP Service
#### Pod 고정 아이피 설정
#### Service가 필요한 이유? 
Pod는 일시적입니다. 삭제되고 다시 만들어지면 IP 주소가 바뀝니다.
## 0010 완료
### - NodePort Service
#### NodePort란?
ClusterIP는 클러스터 내부에서만 접근 가능했습니다. 외부에서 접근하려면 NodePort를 사용합니다.
## 0011 완료
### - LoadBalancer Service
#### LoadBalancer란?
클라우드 환경(AWS, GCP, Azure)에서 외부 로드 밸런서를 자동으로 생성하는 Service 타입입니다.
# 5부: ConfigMap과 Secret
## 0012 완료
### - ConfigMap 사용하기
## 0013 완료
### - Secret 사용하기
# 6부: 스토리지
## 0014 완료
### - PersistentVolume과 PersistentVolumeClaim
# 7부: 실전 애플리케이션 배포
## 0015 완료
### - 애플리케이션 배포