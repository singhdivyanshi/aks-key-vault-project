Hello Everyone!
Few days back I started my DevOps journey and gained various skills, here's my new project:
AKS Key Vault Project
Let me help you with an overview of this project
-This project demonstrates how to use Azure Kubernetes Service (AKS) with Azure Key Vault to manage secrets. 
-It includes a Kubernetes pod that retrieves secrets stored in Azure Key Vault using a managed identity.

Features
AKS Cluster: A managed Kubernetes service to run containerized applications.
Azure Key Vault: A secure storage service for secrets and keys.
Managed Identity: Allows the pod to access Azure resources without needing to manage credentials manually.

Before getting started here are few prerequisites:
An Azure account with an active subscription (Can be your free trial a/c).
Azure CLI installed on your machine (you can refer Azure CLI microsoft for installations).
Basic understanding of Kubernetes concepts.

Installation
Clone the Repository

bash
Copy code
git clone https://github.com/singhdivyanshi/aks-key-vault-project.git
cd aks-key-vault-project
Set Up AKS Follow the steps in this repository to create an AKS cluster.

-Deploy the Application 
-Run the following command to deploy the resources defined in aks-config.yaml:

bash
Copy code
kubectl apply -f aks-config.yaml
Usage
After deployment, you can monitor the status of your pod using:
bash
Copy code
kubectl get pods --namespace default
Notes
Ensure that the Azure Key Vault is configured properly and that your pod has the correct permissions to access the secrets.
Modify the configurations in aks-config.yaml as needed for your specific use case.

Any contributions to improve this project are welcomed :)
