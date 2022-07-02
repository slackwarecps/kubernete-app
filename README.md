# kubernete-app
 Kubernete aplication example
 sdas


 minikube service svc-portal-noticias


kubectl exec -it sistema-noticias -- bash

kubectl exec -it db-noticias -- bash
kubectl exec -it portal-noticias -- bash
cat configuracao.php


mysql -u root -p
show databases;


$host = getenv("HOST_DB");
$usuario = getenv("USER_DB");
$senha = getenv("PASS_DB");
$banco = getenv("DATABASE_DB");

kubectl delete -f ./sistema-noticias.yaml && kubectl apply -f ./sistema-noticias.yaml
kubectl delete -f ./svc-sistema-noticias.yaml && kubectl apply -f ./svc-sistema-noticias.yaml

kubectl delete -f ./svc-portal-noticias.yaml && kubectl apply -f ./svc-portal-noticias.yaml



kubectl delete -f ./db-noticias.yaml && kubectl apply -f ./db-noticias.yaml
kubectl delete -f ./svc-db-noticias.yaml && kubectl apply -f ./svc-db-noticias.yaml


kubectl apply -f ./db-configmap.yaml && kubectl apply -f ./sistema-configmap.yaml && \
kubectl apply -f ./portal-configmap.yaml

1)aplica as configmaps
2) delete pod sistema-noticias
3) aplly o sistema-noticias




### conectando
  usuario e senha  admin/admin

    IP_SISTEMA
