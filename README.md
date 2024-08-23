In this project I am going to deploy mern stack using terraform,docker sonarcube, jenkins,eks ,ecr,argocd and monitor using prometheus and grafana.

Step 1: create a jenkins server diretly on aws console using t2x large ubuntu 22.04 instance so that we can install terraform, jenkins , docker, tivy and sonarcube using userdata

Step 2: Login to jenkins and install plugins for aws they are aws crentials and pipeline: aws and store aws crednetails on global using iam access keys

Step 3: configure terraform path and terraform plugin on the jenkins /usr.bin/terraform path and pipelinestage view also 

Step 4 : Deploying eks cluster using jenkins using git repo 

step 5: create a jump server in same vpc as eks cluster so that we can check eks cluster