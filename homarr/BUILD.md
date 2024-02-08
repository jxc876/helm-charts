# Build & Install

* `helm lint .`
* `helm package .`
* `helm install my-chart -n homarr /Users/mike/dev/helm-charts/homarr/homarr-0.1.0.tgz`

# View

* `k get all -n homarr`
* `k port-forward -n homarr service/homarr-svc 8080:80`

# Remove

`helm uninstall my-chart -n homarr`
