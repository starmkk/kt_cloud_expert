# 어디선가 참고할것만 같은 페이지

- Jenkins는 일련의 작업의 순서들의 집한인 Pipeline을 통해 CI/CD 파이프라인을 구축하는데 도움을 줘요.
- Jenkins의 Pipeline Script는 Groovy 문법에 기반해 있어요.
- 클라우드 환경은 이용한 만큼 비용이 더 나와요.
- CI/CD는 컨테이너 환경을 사용하면 더 효율적으로 구축할 수 있지만, 개념상으로는 필수는 아니에요.
- IaC가 암호를 저장하기 위한 저장소를 의미하지는 않아요.
- ArgoCD는 쿠버네티스의 리소스를 GitOps로 더욱 효율적으로 관리하고 배포 현황을 살펴보는데 아주 유용한 도구에요.
- Git과 오토스케일링은 관계가 없어요.
- 쿠버네티스는 컨테이너 오케스트레이션 플랫폼이에요.
- 도커 이미지를 빌드할 때에는 `docker build ~~~` 명령어를 사용해요.
- Github Action에서 다음 블록의 이미는 ubuntu-lastest 환경에서 실행된다는 의미에요.

```yaml
jobs:
  build:
    runs-on: ubuntu-latest
  ...
```