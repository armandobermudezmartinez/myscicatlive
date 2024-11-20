# SciCatLive with Kubernetes manifests

Explore the metadata catalog with Kubernetes deployments. For a Scicat guide please see [original documentation](https://scicatproject.github.io/documentation/).

This project requires kubernetes kubectl, API server, etcd, controller manager, scheduler, kubelet, and also important, enabled ingress. It has been tested using Microk8s.

## Steps

</details markdown="1">
<br>

1. Clone the repository
   ```sh
   git clone https://github.com/armandobermudezmartinez/myscicatlive
   ```
2. Run with the following command inside the directory
   ```sh
   kubectl apply -Rf services
   ```
