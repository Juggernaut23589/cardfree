# CardFree Implementation

 1. create root folder (cardfree)
 2. create html file  (cardfree.html)
 3. create dockerfile with html file
 4. push image to dockerhub
 5. in the root dirctory (cardfree), create the following eks resources: iam role, eks cluster, node group, security group,vpc, public subnet,route table association and internet gateway.
 6. in the root folder create folder for kubernetes manifest (cardfreeapp)
create kubernetes manifest (yaml files) pods.yaml, service.yaml and ingress.yaml
7. execute terraform init, plan and apply to provision aws resources
8. execute kubectl apply -f command to get the cluster running with the pods and services
9. describe servics to see the details of the ingress service, and retrieve the external ip address and put in web browser to see cardfree page running
```
