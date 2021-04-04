# Kubernetes-intro


## Подготовка окружения

1. kubectl
2. minikube
3. minikube start

## Почему системные поды восстанавливаются после удаления

1. coredns - Deployment spec.replicas:1
2. kube-proxy - DaemonSet - поды запускаются на всех нодах кластера
3. etcd, apiserver, scheduler, controller-manager - static pods, запускаются kubelet'ом

## web-pod

1. Dockerfile на базе nginx
2. web-pod.yaml

## hipster frontend

1. healthy - добавлены переменные окружения, необходимые для запуска процесса
