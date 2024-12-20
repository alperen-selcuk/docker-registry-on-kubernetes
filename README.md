# docker-registry-on-kubernetes

with this repository, you can set up a Docker registry that allows you to securely push and pull images over HTTPS.

first you need install cert-manager for ssl sertificates with signed lets encrypted. 

```
kubectl apply -f cert-manager/ .
```
