- Docker Host = Kubernetes Worker Node
## Two Types of Clusters
- Control Plane cluster 
    - all 4 components (kube-api | etcd | kube_scheduler | kube-controller ) are installed as conatainers
    - iska fayda ye hai ki if eg kube_scheduler goes down still application will be running
- System mode installation (hardway installation) 
    - all 4 components (kube-api | etcd | kube_scheduler | kube-controller ) are installed as services
    - matlab agar ek service down hui to application down
## Kubeadm
- when setting up a cluster using control plane we need an installation utility called **Kubeadm**
- koi bhi chez install karni hai cluster pe to we need Kubeadm
