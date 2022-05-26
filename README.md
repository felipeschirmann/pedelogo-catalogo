building: 
``bash build.sh <version>``

uploading:
``bash upload.sh <version>``

Deploy:
``kubectl apply -f k8s/api/Deployment.yaml``
``kubectl apply -f k8s/mongodg/Deployment.yaml``

Services: 
``kubectl apply -f k8s/api/Service.yaml``
``kubectl apply -f k8s/mongodg/Service.yaml``

port-forward:
``kubectl port-forward service/api-service 8080:80``