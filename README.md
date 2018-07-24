# kubernetes-metallb

## Start
minikube start  
minikube dashboard  

kubectl apply -f metallb.yaml  
kubectl apply -f example-layer2-config.yaml  
kubectl apply -f tutorial-2.yaml  
  
kubectl get services  
  
curl 192.168.99.240
