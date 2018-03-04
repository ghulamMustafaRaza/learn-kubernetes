# Deploy a StateLess Application

```bash
kubectl apply -f simple-deployment.yml

kubectl get svc

kubectl get deployment

minikube service nginx
```

# Deploy a StateFull Application
```bash
kubectl get svc # get all old Services

kubectl get deployment # get all old Deployment

kubectl get pods # get all old Pods

kubectl apply -f mongodb-presist-mongo-db.yml #Apply New Chages

kubectl get svc # get all Services

kubectl get deployment # get all Deployment

kubectl get pods # get all Pods

kubectl get pv # get all presist volume

kubectl get pvc # get all presist volume claim
```