# Build & Install

* `helm lint .`
* `helm package .`
* `helm install my-chart -n homarr ./homarr-0.1.0.tgz -f local-values.yaml`

# View

* `k get all -n homarr`
* `k port-forward -n homarr service/homarr-svc 8080:80`

# Debug

* `helm template . -f local-values.yaml`

# Remove

`helm uninstall my-chart -n homarr`
