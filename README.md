docker build -t [your-docker-repo]/dapr-k8s-secrets:1.0.0 .

docker push [your-docker-repo]/dapr-k8s-secrets:1.0.0

kubectl apply -f .\deployment.yaml