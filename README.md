# sample-demo-networkpolicies

Clone Repo

git clone https://github.com/saikrishnaoduru841/sample-demo-networkpolicies.git

cd sample-demo-networkpolicies

kubectl apply -f pods.yaml

kubectl apply -f service.yaml

kubectl apply -f networkpolicies.yaml

# If you want to delete 

kubectl delete -f networkpolicies.yaml

kubectl delete -f service.yaml

kubectl delete -f pods.yaml

Go to browser 

paste external service loadbalancer Ip with port 8080  IP:8080
paste internal service loadbalancer IP with port 8080  IP:8080

# In network policies networkpolicies.yaml this file allows to communicate with external, internal.  It will db-service 8080
# In network policies networkpolicies-blockinternal.yaml this file blocks to communicate with internal.   





