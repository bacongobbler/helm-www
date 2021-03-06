---
title: "Helm Search Hub"
---

## helm search hub

헬름 허브 또는 모노큘러 인스턴스에서 차트 검색

### 개요


헬름 차트에 대한 헬름 허브 또는 모노큘러 인스턴스를 검색한다.

헬름허브는 공개적으로 사용 가능한 분산 형 차트에 대한 
중앙 집중식 검색을 제공한다. 헬름 프로젝트에서 관리한다. 
https://hub.helm.sh에서 방문 할 수 있다.

모노큘러(Monocular)는 여러 헬름 차트 저장소에서 차트를 
검색 할 수있는 웹 기반 애플리케이션이다. 헬름 허브를 구동하는 코드베이스이다.
https://github.com/helm/monocular에서 찾을 수 있다.


```
helm search hub [keyword] [flags]
```

### Options

```
      --endpoint string      차트에 대해 질의할 모노큘러 인스턴스 (기본값 "https://hub.helm.sh")
  -h, --help                 helm search hub 명령어에 대한 도움말
      --max-col-width uint   출력 테이블의 최대 열 너비 (기본값 50)
  -o, --output format        지정된 형식으로 출력. 허용되는 값: table, json, yaml (기본값 table)
```

### 부모 명령어에서 상속된 옵션들

```
      --debug                       장황한(verbose) 출력 활성화
      --kube-apiserver string       쿠버네티스 API 서버의 주소 및 포트
      --kube-as-group stringArray   작업에 관해 제시할 그룹. 플래그를 여러 번 사용하여 여러 그룹 지정 가능
      --kube-as-user string         작업에 관해 제시할 사용자명
      --kube-context string         사용할 kubeconfig 컨텍스트 이름
      --kube-token string           인증에 사용될 베어러(bearer) 토큰
      --kubeconfig string           kubeconfig 파일 경로
  -n, --namespace string            이 요청에 대한 네임스페이스 스코프
      --registry-config string      레지스트리 구성 파일에 대한 경로 (기본값 "~/.config/helm/registry.json")
      --repository-cache string     캐시된 저장소 색인이 포함된 파일의 경로 (기본값 "~/.cache/helm/repository")
      --repository-config string    저장소 이름 및 URL 을 포함하는 파일 경로 (기본값 "~/.config/helm/repositories.yaml")
```

### 함께 보기

* [helm search](helm_search.md)	 - 차트에서 키워드 검색

###### Auto generated by spf13/cobra on 29-Oct-2020
