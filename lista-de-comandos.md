kubectl apply -f ./portal-noticias.yaml
kubectl delete pod portal-noticias
kubectl get nodes -o wide
kubectl get pods
kubectl get svc
kubectl get configmap

kubectl exec -it portal-noticias -- bash

Starting Service in Mac
minikube start --driver=docker --extra-config=apiserver.service-node-port-range=32760-32767 --ports=127.0.0.1:32760-32767:32760-32767