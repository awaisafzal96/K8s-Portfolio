# K8s Portfolio

This project is my personal portfolio website deployed using **Kubernetes**.  
It shows how to containerize an app with Docker and run it on a Kubernetes cluster (Kind).

---

## Files in This Project
- **Dockerfile** → Build the app image  
- **deployment.yaml** → Deploy the app on Kubernetes  
- **service-nodeport.yaml** → Expose the app outside the cluster  
- **configmap.yaml** → Store app settings  
- **secret.yaml** → Store sensitive data  
- **pv-pvc.yaml** → Persistent storage  
- **hpa.yaml** → Auto scaling  
- **ingress.yaml** → Route traffic to the app  
- **portfolio-chart/** → Helm chart for deployment  

