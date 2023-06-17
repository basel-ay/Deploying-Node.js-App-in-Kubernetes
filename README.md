# Deploying-Node.js-App-in-Kubernetes

## Dockerfile

![image](https://github.com/basel-ay/Deploying-Node.js-App-in-Kubernetes/assets/64821137/d74b3f47-6d92-47d0-9224-b4939fb4d739)


## Commands 

`minikube status`

![image](https://github.com/basel-ay/Deploying-Node.js-App-in-Kubernetes/assets/64821137/ba4c3f3b-924e-4b0c-9bdd-e61f838ecb18)

`kubectl create deployment k8s-web-server --image=baselayman/k8s-web-server`

`kubectl expose deployment k8s-web-server --type=NodePort --port=3000`

![image](https://github.com/basel-ay/Deploying-Node.js-App-in-Kubernetes/assets/64821137/815de841-a5e5-4bed-b734-d9c520724e84)

`kubectl get services`

![image](https://github.com/basel-ay/Deploying-Node.js-App-in-Kubernetes/assets/64821137/970763ae-5145-47b2-8479-cf13a48a8d54)

`minikube service k8s-web-server` or `kubectl port-forward service/k8s-web-server 3000:3000`

![image](https://github.com/basel-ay/Deploying-Node.js-App-in-Kubernetes/assets/64821137/0f94dbbf-9b2b-4241-802e-d0773cd602cb)

![image](https://github.com/basel-ay/Deploying-Node.js-App-in-Kubernetes/assets/64821137/255ec0ac-4b6e-4dde-bf1f-3badb4c0c873)

## Output

![image](https://github.com/basel-ay/Deploying-Node.js-App-in-Kubernetes/assets/64821137/7b7eff91-c777-45d8-8e08-5be8727a0c00)
