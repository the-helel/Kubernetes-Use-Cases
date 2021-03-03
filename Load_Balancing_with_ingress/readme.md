# Commands


## $ minikube addons enable ingress
## $ kubectl create deployment maild --image=vimal13/mailapp:v1
## $ kubectl scale deployment maild --replicas=2
## $ kubectl create deployment searchd --image=vimal13/searchapp:v1
## $ kubectl scale deployment searchd --replicas=3
## $ kubectl expose deploy maild --port=80 --type=NodePort
## $ kubectl expose deploy searchd --port=80 --type=NodePort
## $ kubectl create -f ingress.yml

## Dont Forget to add hosts

## SYNTAX: curl [YOUR_HOST_NAME]/search
