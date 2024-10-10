App-Chart

Installs generic app

$ helm repo add app-chart https://glauciolabs.github.io/app-chart
$ helm install --create-namespace --namespace <namespace> <app-name> app-chart/app-chart -f values.yaml]