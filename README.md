# GCP-Kubernetes_project
gcloud container clusters create project1 --num-nodes=1 --zone=us-central1
gcloud container clusters get-credentials project1 --zone us-central1 --project golden-centaur-399223
docker pull amalmadhavan101/my-flaskapp:my-flaskapp
kubectl apply -f flask-app-deployment.yaml
kubectl apply -f redis-deployment.yaml
