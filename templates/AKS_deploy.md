Azure AKS :

az aks create \
    --resource-group flaskgroup \
    --name flaskcluster \
    --node-count 1 \
    --generate-ssh-keys \
    --attach-acr flaskportfolio

Referecnes for deploying on free hosting service:

https://medium.com/swlh/how-to-host-your-flask-app-on-pythonanywhere-for-free-df8486eb6a42