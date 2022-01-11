# k8s-microservices-vote.app

commands:
- kubectl create namespace voteapp
- kubectl apply -f . -n voteapp
- kubectl get all -n voteapp
- kubectl delete all --all -n voteapp

- minikube service name_service