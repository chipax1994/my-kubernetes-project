# Deploying mongodb and mongo-express applications on kubernetes
deploying mongodb and mongo-express applications on kubernetes ....
first,the following dependencies needed for the deploymennt were downloaded virtualbox,minikube, kubectl, kubens....


secondly,the following .yaml configuration files were configured mongo.yaml deployment file and mongo service,mongo-secrets.yaml was created to protect sensitive informations like usernames and passwords which were then encoded in a base64 format.....


Mongo-express .yaml deployment file was configured, both mongodb and mongo express services where connected together using Configmap.yaml
Ingress.yaml was then configured to connect the kubernetes clusters to external services.....


kubernetes Deployments,services,pods and namespaces were created

