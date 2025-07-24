# minikube
hier findest service.yaml dateien für minikube
  nginx-service-00.yaml: 
    kopiere/klone https://github.com/GBPI-Quant/minikube/
    führe die Befehle durch:
      -> minikube mount $(pwd)html:/html
      -> kubectl port-forward service/nginx-local-service 8081
      -> curl http://localhost:8081 
  
