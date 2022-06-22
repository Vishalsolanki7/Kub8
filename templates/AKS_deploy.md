Azure AKS :

az aks create \
    --resource-group flaskgroup \
    --name flaskcluster \
    --node-count 1 \
    --generate-ssh-keys \
    --attach-acr flaskportfolio

