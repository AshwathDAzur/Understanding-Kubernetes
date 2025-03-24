# Understanding-Kubernetes
Gaining foundational knowledge of Kubernetes, including container orchestration, deployment management, and scaling applications efficiently.

### Setting up minikube

```bash
curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64

chmod +x minikube-linux-amd64

sudo mv minikube-linux-amd64 /usr/local/bin/minikube

minikube version
```

![setup_minikube.png](assets/setup_minikube.png)

### Setting up kubectl

```bash
curl -LO "https://dl.k8s.io/release/$(curl -L -s https://dl.k8s.io/release/stable.txt)/bin/linux/amd64/kubectl"

chmod +x kubectl

sudo mv kubectl /usr/local/bin/

kubectl version --client
```

![setup_kubectl.png](assets/setup_kubectl.png)

### Setting up Kubernetes cluster

```bash
minikube start
```

![setup_cluster.png](assets/setup_cluster.png)