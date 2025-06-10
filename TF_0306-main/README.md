# Exercício Minikube na aula de implantação de servidores

Este repositório contém os arquivos e instruções para implantar uma aplicação Nginx em um cluster local usando Minikube e kubectl.

## Pré-requisitos

- [Minikube](https://minikube.sigs.k8s.io/docs/)
- [kubectl](https://kubernetes.io/docs/tasks/tools/)
- Git

### 1. Iniciar o Minikube
- minikube start

### Comandos para criar o Deployment e o Services:
- kubectl apply -f nginx-deployment.yaml
- kubectl apply -f nginx-service.yaml


### Comandos para verificar o Deployment, pods, services e detalhes dos pods:
- kubectl get deployments
- kubectl get pods
- kubectl get services
- kubectl describe pod <nome-do-pod>

### Comandos para verificar o Deployment, pods, services e detalhes dos pods:
- kubectl delete -f nginx-service.yaml
- kubectl delete -f nginx-deployment.yaml

### Imagens
![Nginx no navegador] (image.png)
![5 pods rodando] (image-1.png)
