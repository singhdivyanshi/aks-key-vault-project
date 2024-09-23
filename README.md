Hello Everyone!
Few days back I started my DevOps journey and gained various skills, here's my new project:

AKS Key Vault Project

This project demonstrates how to use Azure Kubernetes Service (AKS) with Azure Key Vault to manage secrets. 
It includes a Kubernetes pod that retrieves secrets stored in Azure Key Vault using a managed identity.


Features

AKS Cluster: A managed Kubernetes service to run containerized applications.

Azure Key Vault: A secure storage service for secrets and keys.

Managed Identity: Allows the pod to access Azure resources without needing to manage credentials manually.


Before getting started here are few prerequisites:

1.An Azure account with an active subscription (Can be your free trial a/c).

2.Azure CLI installed on your machine (you can refer Azure CLI microsoft for installations).

3.Basic understanding of Kubernetes concepts.


Installation--

1.Clone the Repository-
   
   git clone https://github.com/singhdivyanshi/aks-key-vault-project.git
   cd aks-key-vault-project

2.Set Up AKS

3.Deploy the Application--

  Run the following command to deploy the resources defined in aks-config.yaml:  
  (kubectl apply -f aks-config.yaml)

Usage--

After deployment, you can monitor the status of your pod using: 
(kubectl get pods --namespace default)

Notes
Ensure that the Azure Key Vault is configured properly and that your pod has the correct permissions to access the secrets.
Modify the configurations in aks-config.yaml as needed for your specific use case.

Any contributions to improve this project are welcomed :)
