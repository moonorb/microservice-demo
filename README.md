# Microservice-Demo Application

This code can be used as a demo application for any OpenTelemetry project. There are 3 microservices.

The original Java Code supported only docker([Paul Chapman's GitHub](https://github.com/paulc4/microservices-demo)).  


This repo has some minor edits so it support Microservice Architecture and can be deployed in a K8s cluster. 

![Alt text](https://github.com/moonorb/microservice-demo/blob/main/images/microservice-demo.PNG)

### Deploy Microservice-Demo on Kubernetes

```
kubectl create -f k8s/ -n microservice-demo
```




