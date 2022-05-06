# k8s-examen
## Examen: Déploiement-kubernetes
### Introduction: 
 On va créer 2 deploiements redis et cloud.canister.io:5000/arhturescriou/node-redis
### Command
#### Database redis:
 ```kubectl create -f dat_deploy_redis.yaml``` <br>
 ```inline code`kubectl create -f dat_service_redis.yaml``` <br>
#### Web app
```inline code` kubectl create -f dat_webapp.yaml```<br>  
```inline code` kubectl create -f dat_webapp_service.yaml```<br>
