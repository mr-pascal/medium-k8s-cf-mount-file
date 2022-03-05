

# medium-k8s-cf-mount-file


```sh

### Port forward port to Deployment
kubectl port-forward deployment/nginx 8080:80

### Apply Deployment
kubectl apply -f deployment.yaml

### Apply Deployment
kubectl apply -f deployment.yaml

### Apply all YAML files
kubectl apply -f .

### Get all resources
kubectl get all

### Get all by label
kubectl get all -l name=nginx

### Get Pod by label
kubectl get po -l name=nginx

### Restart deployments
kubectl rollout restart deployment/nginx


```