## 📌 Objective

Deploy and manage applications in Kubernetes using Minikube, `kubectl`, and Docker.

---

## 🛠️ Tools Used

- [Minikube](https://minikube.sigs.k8s.io/docs/)
- [kubectl](https://kubernetes.io/docs/reference/kubectl/)
- [Docker](https://www.docker.com/)

---

## 📁 Project Structure

Task5/ ├── deployment.yaml # Defines the Deployment for the application ├── service.yaml # Exposes the Deployment as a Service ├── pic1.jpg # Screenshot of pods ├── pic2.jpg # Screenshot of services

---

## 🚀 Steps to Deploy the Application

1. **Start Minikube:**

   ```bash
   minikube start
   
2. **Apply the Deployment:**

   ```bash
   kubectl apply -f deployment.yaml

3. **Apply the Service:**

  ```bash
  kubectl apply -f service.yaml

4. **Verify the Pods:**

   ```bash
   kubectl get pods

5. **Verify the Services:**

   ```bash
   kubectl get services

6. **Scale the Deployment (e.g., to 3 replicas):**

   ```bash
   kubectl scale deployment <deployment-name> --replicas=3

7. **Describe the Pod for Detailed Information:**

   ```bash 
   kubectl describe pod <pod-name>

8. **View Logs of a Pod:**

  ```bash
  kubectl logs <pod-name>

