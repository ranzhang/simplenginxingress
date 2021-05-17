# simplenginxingress
This is a minimalistic example to demo an nginx ingress controller using the new v1 syntax (vibeta is deprecated). It consists of:
an nginx ingress resource file (purposely with two routes to the same service)
a clusterIP service 
a deployment with 1 replica running nginx

To deploy the setup:
kubectl create -f https://raw.githubusercontent.com/ranzhang/simplenginxingress/main/nginx.yaml

