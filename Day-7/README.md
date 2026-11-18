# Kubernetes Architecture

- Kubernetes nodes are divided into 2 types, **master node (control plane)** and **worker node** 

## Master Node

- Master is responsible for managing the complete cluster.
- You can access master node via the CLI, GUI, or API.
- The master watches over the nodes in the cluster and is responsible for the actual orchestration of containers on the worker nodes.
- For achieving fault tolerance, there can be more than one master node in the cluster.

### Master Node (Control Plane) components
- API Server
- ETCD
- Controller Manager
- Scheduler

### Worker Node Components
- Kubelet
- Container Runtime
- Kube-Proxy

![What is POD](../images/pod.png "What is POD")


### Contributors
[![Yogendra Pratap Singh][yogendra_avatar]][yogendra_homepage]<br/>[Yogendra Pratap Singh][yogendra_homepage] 

  [yogendra_homepage]: https://www.linkedin.com/in/yogendra-pratap-singh-41630716b/
  [yogendra_avatar]: https://img.cloudposse.com/75x75/https://github.com/PratapSingh13.png