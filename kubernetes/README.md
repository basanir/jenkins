1. Install and set up a Kubernetes cluster. This can be done using tools like kubeadm or by using a managed Kubernetes service like Google Kubernetes Engine (GKE) or Amazon Elastic Container Service for Kubernetes (EKS).

2. Create a namespace for Jenkins. This can be done using the following command:
  ```bash
    kubectl create namespace jenkins
  ```

3. Deploy jenkins using a helm or using a deployment yaml file and apply
helm command to deploy jenkins 
  ```bash
    helm install jenkins stable/jenkins -n jenkins
  ```

4. Expose the Jenkins service. By default, the Jenkins service is only accessible within the cluster.


