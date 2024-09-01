올리브영 서버 이미지들을 쿠버네티스 클러스터에 배포를 위해 제작된 `yaml` 파일들입니다.

서버는 두 개의 스프링 서버로 만들어졌으며 해당 리포지토리를 `ArgoCD`에 연결하여 배포 자동화를 진행했습니다.

- `main`
- `shutter`

``` bash
.
├── k8s
│   ├── ingress.yaml
│   ├── main-deployment.yaml
│   ├── main-service.yaml
│   ├── shutter-deployment.yaml
│   └── shutter-service.yaml
└── readme.md

2 directories, 6 files
```