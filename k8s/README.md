`kubectl apply -f angular-deployment.yaml`

`kubectl apply -f angular-service.yaml`

`kubectl apply -f db-deployment.yaml`

`kubectl apply -f db-service.yaml`

`kubectl apply -f spring-boot-deployment.yaml`

`kubectl apply -f spring-boot-service.yaml`

`kubectl apply -f docker-spring-angular-networkpolicy.yaml`

`kubectl port-forward service/spring-boot 8080:8080`

`kubectl port-forward service/angular 4200:80`
