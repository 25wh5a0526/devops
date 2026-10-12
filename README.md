docker build -t todo-app .
docker run -d -p 8080:80 --name todo-container todo-app

kuber
docker --version
kubectl version --client
kubectl get nodes
docker build -t todo-app .
kubectl create deployment todo-app --image=todo-app
kubectl get deployments
kubectl get pods
kubectl port-forward deployment/todo-app 8080:80
