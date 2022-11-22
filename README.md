## DevSecOps

jenkins pipeline URL

http://devsecops-pro.eastus.cloudapp.azure.com/8080


## NodeJS Microservice - Docker Image -
`docker run -p 8787:5000 theeraphonp/node-service:v1`

`curl localhost:8787/plusone/99`
 
## NodeJS Microservice - Kubernetes Deployment -
`kubectl create deploy node-app --image theeraphonp/node-service:v1`

`kubectl expose deploy node-app --name node-service --port 5000 --type ClusterIP`

`curl node-service-ip:5000/plusone/99`

## DevSecOps Pipeline Tool lists -
- Kubernetes
- Docker 
- Azure 
- Jenkins
- SonarQube
- Mutation Test
- Dependency Check
- Trivy (free source for vulnerabilities scanning)
- OPA conftest (IaC files statical scanning)
- Kubesec
- ZAP (VA open source)

