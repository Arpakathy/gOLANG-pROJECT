## Deploying the Helm Chart

##  Package the Helm chart:

helm package my-go-app

helm install my-go-app ./my-go-app --set port=9090

helm install my-go-app ./my-go-app --set port=9090
