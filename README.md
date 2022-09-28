# Congifured-AKS-to-host-a-Service
## Deployed an Eternal and Internal Service on AKS using Docker Images in ACR

Task 1: Created a resource group and an Azure Container Registry in US East using Azure Cloud Shell

<img width="960" alt="acr created" src="https://user-images.githubusercontent.com/110430121/192762920-4c885d8c-d803-4f52-8e2c-75642fe830ab.png">

Task 2: Created a Dockerfile, built a container from it, and pushed it to Azure Container Registry

<img width="960" alt="docker build successful" src="https://user-images.githubusercontent.com/110430121/192763880-dc8dab8a-9bef-4371-9269-58c01ac077c8.png">

Task 3: Created an Azure Kubernetes Service cluster to run the containers.

Task 4: Granted the AKS cluster permissions to access the ACR by giving it the acrpull role assignment

<img width="960" alt="ks role assigned" src="https://user-images.githubusercontent.com/110430121/192764740-0e4b9c70-a1d3-48b5-a386-42489fd6e577.png">

Task 5: Deployed an external service to AKS

<img width="960" alt="ip address of k8service" src="https://user-images.githubusercontent.com/110430121/192765211-ec8965c4-1d11-4d0e-a4a0-8a4a9d10a2c7.png">

Task 6: Verified that I can access an external AKS-hosted service

<img width="960" alt="welcomyaaah" src="https://user-images.githubusercontent.com/110430121/192765623-b973a82b-d3d9-4fe7-a8d6-8329d55e60b6.png">

Task 7: Deploy an internal service to AKS

<img width="960" alt="nginx internal" src="https://user-images.githubusercontent.com/110430121/192765928-233b0252-699e-44c4-a73a-51f52d2314c5.png">

Task 8: Verified that I can access an internal AKS-hosted service

<img width="960" alt="finished 09" src="https://user-images.githubusercontent.com/110430121/192764403-162265e0-6c17-406f-94cd-344c89437017.png">

