 kubectl -n pgo apply -f postgres-k8s/postgres-db-pv.yaml 
 kubectl -n pgo apply -f postgres-k8s/postgres-db-pvc.yaml 
 kubectl -n pgo apply -f postgres-k8s/postgres-secret.yaml 
 kubectl -n pgo apply -f postgres-k8s/postgres-db-deployment.yaml 
 kubectl -n pgo apply -f postgres-k8s/postgres-db-service.yaml 
