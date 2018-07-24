# kubernetes-metallb

minikube start
minikube dashboard

kubectl apply -f metallb.yaml
kubectl apply -f example-layer2-config.yaml
kubectl apply -f tutorial-2.yaml

kubectl get services
NAME         CLUSTER-IP      EXTERNAL-IP      PORT(S)        AGE
kubernetes   10.96.0.1       <none>           443/TCP        16m
nginx        10.108.240.10   192.168.99.240   80:32321/TCP   8m

curl 192.168.99.240
