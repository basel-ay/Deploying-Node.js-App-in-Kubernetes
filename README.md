# Deploying-Node.js-App-in-Kubernetes

## Dockerfile

![image](https://github.com/basel-ay/Deploying-Node.js-App-in-Kubernetes/assets/64821137/1532bf53-8d4b-42af-afdc-24b18b7df781)


## Commands 

`minikube status`

![image](https://github.com/basel-ay/Deploying-Node.js-App-in-Kubernetes/assets/64821137/d03f7e21-f912-4984-9f48-80835691d05b)

`kubectl create deployment k8s-web-server --image=baselayman/k8s-web-server`

`kubectl expose deployment k8s-web-server --type=NodePort --port=3000`

![image](https://github.com/basel-ay/Deploying-Node.js-App-in-Kubernetes/assets/64821137/5f1fc7e2-1b47-454a-942d-7f9e45cfc02b)

`kubectl get svc`

![image](https://github.com/basel-ay/Deploying-Node.js-App-in-Kubernetes/assets/64821137/97de8a81-6d39-4f3a-bf47-62f646a0fd59)

`minikube service k8s-web-server` or `kubectl port-forward service/k8s-web-server 3000:3000`

![image](https://github.com/basel-ay/Deploying-Node.js-App-in-Kubernetes/assets/64821137/41ce81b7-afff-4eb7-873d-3a948de56f7f)

![image](https://github.com/basel-ay/Deploying-Node.js-App-in-Kubernetes/assets/64821137/87b8ce63-9e41-49cc-8ea1-85ce035cad96)

## Output

![image](https://github.com/basel-ay/Deploying-Node.js-App-in-Kubernetes/assets/64821137/7af7d924-ec4d-41a0-93bc-0b85ec3e9ad7)
