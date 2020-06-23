**1. Online Boutique**, https://github.com/GoogleCloudPlatform/microservices-demo

| Service | Build, Deploy | Observability |
| ------------------------- | ---------------- | ---------------- |
|                     | Azure Kubernetes (Done ✅) | |
|                     | AWS Kubernetes | |
| 1. emailservice (Python) | | |
| 2. productcatalogservice (Go) | | |
| 3. recommendationservice (Python) | | |
| 4. shippingservice (Go) | | |
| 5. checkoutservice (Go) | | |
| 6. paymentservice (Node.js) | | |
| 7. currencyservice (Node.js) | | |
| 8. cartservice (C#) | [<img src="https://storage.googleapis.com/cloudrun/button.svg" alt="Run on Google Cloud" height="30">][run_cartservice] | |
| 9. frontend (Go) | [<img src="https://storage.googleapis.com/cloudrun/button.svg" alt="Run on Google Cloud" height="30">][run_frontend] | |
| 10. adservice (Java) | | |

[run_frontend]: https://deploy.cloud.run/?git_repo=https://github.com/GoogleCloudPlatform/microservices-demo&dir=src/frontend
[run_cartservice]: https://deploy.cloud.run/?git_repo=https://github.com/GoogleCloudPlatform/microservices-demo&dir=src/cartservice


**Azure Kubernetes**
1. az login
2. az acr create --name <microservices> --resource-group <microservices-demo> --sku basic
3. az aks create --resource-group <microservices-demo> --name <microservices-demo> --node-count 3 --attach-acr <microservices> --enable-addons monitoring --generate-ssh-keys
4. az aks get-credentials --resource-group <microservices-demo> --name <microservices-demo>
5. skaffold run --default-repo=<>.azurecr.io
