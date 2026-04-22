# HELM CHART (K8S)

This is a repository to host a Helm chart during some tests and practices :)

## uses :
1. add this in your local with this command  :
   ```helm repo add mouad5-bot https://mouad5-bot.github.io/helm-chart/```
2.  search repo : ```helm search repo nginx```
3.  deploy : 
   ```helm install <release-name> <repo/image or mouad5-bot/nginx>```

## other commands:
-  ```helm template <temp-name>``` to see the all the manifest you generated from the template.
-  ```helm package <path to your helm-chart>``` to package your helm-chart as a .tgz folder.
-  ```helm repo index .``` to generate the index.yaml which contain the infos of chart
-  
