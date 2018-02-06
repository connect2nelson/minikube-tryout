# minikube-tryout
trying out a minikube to spawn a hello-world application

Deploying a sample nodejs application via docker to a containerized cluster created via minikube.

Some helpful commands : 
docker build -t hello-node:v1
eval $(minikube docker-env)
docker build -t hello-node:v1
kubectl run hello-node --image=hello-node:v1 --port=8080
kubectl get deployments
kubect get pods
kubectl get pods
kubectl get events
kubectl config view
kubectl expose deployment hello-node --type=LoadBalancer
kubectl get services
minikube service hello-node
