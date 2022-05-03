create root folder (cardfree)
create html file  (cardfree.html)
create dockerfile with html file
push image to dockerhub
in the root dirctory (cardfree) terminal, initiate terraform
create the following eks resources: iam role, eks cluster, node group, security group,vpc, public subnet,route table association and internet gateway
do terraform plan and terraform apply to deploy
in the root folder create folder for kubernetes manifest  (cardfreeapp)
create kubernetes manifest (yaml files) pods.yaml, service.yaml and ingress.yaml
do kubectl apply -f command to get the cluster running with the pods and services
do kubectl describe servics to see the details of the ingress service 
get the external ip address and put in web browser to see cardfree page running
