# docker-registry-on-kubernetes

with this repository, you can set up a Docker registry that allows you to securely push and pull images over HTTPS.

first you need install cert-manager for ssl sertificates with signed lets encrypted. 

install cert-manager on kubernetes

```
kubectl apply -f https://github.com/cert-manager/cert-manager/releases/download/v1.13.1/cert-manager.yaml
```

after that you install registry manifest wtih clone this repository.


```
kubectl apply -f registry-manifests/ . 
```
