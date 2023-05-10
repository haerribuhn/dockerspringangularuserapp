# Minikube
`minikube start`

## Kubernetes files
Kubernetes files generated with komposer from docker-compose file.

`kubectl apply -f angular-deployment.yaml`

`kubectl apply -f angular-service.yaml`

`kubectl apply -f db-deployment.yaml`

`kubectl apply -f db-service.yaml`

`kubectl apply -f spring-boot-deployment.yaml`

`kubectl apply -f spring-boot-service.yaml`

`kubectl apply -f docker-spring-angular-networkpolicy.yaml`

### Port forwarding
`kubectl port-forward service/spring-boot 8080:8080`

`kubectl port-forward service/angular 4200:80`

### Alternative Ingress
Not working !!!!

`kubectl apply -f ingressyaml`
