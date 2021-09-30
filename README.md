# rotten-potatoes-k8s

- Criando o cluster com kind

kind create cluster --name meucluster --config cluster.yaml

- criando os Pods

kubectl apply -f k8s/deployment.yaml
