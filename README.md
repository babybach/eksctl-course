brew update-reset 

brew tap weaveworks/tap

------------------------------------------

brew install weaveworks/tap/eksctl

time eksctl create cluster -f eks-course.yaml

eksctl get cluster 

kubectl get nodes  

------------------------------------------

brew install helm

helm repo add stable https://charts.helm.sh/stable

helm repo update

helm search repo

helm install redis-test stable/redis

helm ls

kubectl get pod

helm uninstall redis-test 

------------------------------------------

kubectl apply -f https://raw.githubusercontent.com/kubernetes/dashboard/v2.2.0/aio/deploy/recommended.yaml
