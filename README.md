# k8s
kubernetes 

## 常用命令

启动MiniKube    
minikube start     

启动DashBoard   
 minikube dashboard   
 



查看rc   

kubectl get rc   

查看pod   

kubectl get pods   

查看svc  

kubectl get svc    

查看service 对外 url    
minikube service javaweb --url       

查看deployment     
kubectl  describe deployment nginx-deployment

查看pod    
kubectl get pods -l app=nginx     

kubectl describe pod  nginx-deployment-6c54bd5869-9g72w   





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


## Nginx

创建deployment    
kubectl create -f nginx-deployment.yaml       

## Guestbook  Example
rc    

kubectl create -f redis-master-controller.yaml     
kubectl get rc  

kubectl get pods  

service  

kubectl create -f redis-master-service.yaml   
kubectl get services   
kubectl create -f redis-slave-controller.yaml     
kubectl create -f redis-slave-service.yaml     
kubectl create -f frontend-controller.yaml    
kubectl create -f frontend-service.yaml  


