yum install git
git clone https://github.com/vipin-k/kubernetes-ingress.git
cd kubernetes-ingress/
cd deployments/
kubectl apply -f common/ns-and-sa.yaml
kubectl apply -f common/default-server-secret.yaml
kubectl apply -f common/nginx-config.yaml
kubectl apply -f common/custom-resource-definitions.yaml
kubectl apply -f rbac/rbac.yaml
kubectl apply -f daemon-set/nginx-ingress.yaml
kubectl get pods -n nginx-ingress
kubectl logs nginx-ingress-ck662 -n nginx-ingress
