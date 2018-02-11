# k8s
kubernetes 

## 常用命令
查看rc   

kubectl get rc   

查看pod   

kubectl get pods   

查看svc  

kubectl get svc    

查看service 对外 url    
minikube service javaweb --url    




## Mysql 
创建RC     

kubectl create -f mysql-rc.yaml     


创建service    

kubectl create -f mysql-svc.yaml   

## javaweb
创建rc      

kubectl create -f javaweb-rc.yaml   
创建 service   
kubectl create -f javaweb-svc.yaml


