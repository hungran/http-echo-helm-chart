# Http Echo Chart

## Usage

Using ghcr.io

```shell
# create a token, login to ghcr.io with
helm registry login ghcr.io
helm pull oci://ghcr.io/hungran/http-echo-helm-chart/http-echo-helm-chart --version 0.1.0
```

Using legacy registry

```shell
helm repo add http-echo-helm-chart https://hungran.github.io/http-echo-helm-chart/
helm pull http-echo-helm-chart/http-echo-helm-chart
```

Using ArgoCD
```shell
  source:
    repoURL: https://github.com/hungran/http-echo-helm-chart.git
    path: charts/http-echo
    targetRevision: "http-echo-0.1.1"
```

## Chart Repo Template

A chart repo template from [TuanAnh](https://github.com/tuananh/chart-repo-template)

## License

[LICENSE](./LICENSE)
