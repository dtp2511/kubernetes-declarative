to apply that config file to connected cluster :
- kubectl apply -f=deployment.yaml

1. if you want to apply multiple configuration files you add more -f option
for example : 
- kubectl apply -f=deployment.yaml -f=deployment2.yaml