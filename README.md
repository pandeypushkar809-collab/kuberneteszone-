  Kubernetes Concepts Practiced

##  Pods
Understanding how containers run inside Kubernetes.

##  Deployments
Managing scalable and self-healing applications.

##  ConfigMaps
Managing application configuration externally.

##  Secrets
Securely storing sensitive information.

##  CronJobs
Running scheduled tasks automatically.

##  DaemonSets
Running workloads on every Kubernetes node.

##  Resource Management
Understanding:
- CPU limits
- Memory limits
- Resource requests
- QoS classes

---

# 🚀 Purpose of This Repository

This repository is created for:
- Kubernetes practice
- DevOps learning
- YAML manifest understanding
- Real-time hands-on lab exercises
- 
kubectl cluster-info
kubectl version
kubectl config view
kubectl config current-context

kubectl get nodes
kubectl describe node <node-name>
kubectl top nodes

kubectl get namespaces
kubectl create namespace dev
kubectl delete namespace dev

kubectl get pods
kubectl get pods -A
kubectl get pods -o wide
kubectl describe pod <pod-name>
kubectl logs <pod-name>
kubectl exec -it <pod-name> -- /bin/bash
kubectl delete pod <pod-name>

kubectl get deployments
kubectl create deployment nginx --image=nginx
kubectl scale deployment nginx --replicas=3
kubectl rollout status deployment nginx
kubectl delete deployment nginx

kubectl get svc
kubectl expose deployment nginx --type=NodePort --port=80

kubectl get configmap
kubectl get secrets
kubectl get cronjobs
kubectl get daemonsets

kubectl apply -f pod.yaml
kubectl delete -f pod.yaml
kubectl edit deployment nginx

The goal is to build strong practical knowledge of Kubernetes and DevOps tools through continuous experimentation and implementation.
