kubectl create -f .\nginx-Pod.yaml
kubectl get Pods
kubectl port-forward nginx 8080:80
kubectl exec -it nginx -- /bin/bash
kubectl apply -f .\fi.yaml
kubectl diff
kubectl delete Pod nginx 
kubectl annotate