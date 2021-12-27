# react-express-hello

npm install -g create-react-app
create-react-app client
npx create-react-app client

docker composer up --build
docker composer up

> push gitlab > gilab automaticly > pull repo -  build image - test code - push code

> push gitlab > gilab automaticly > pull repo -  test image - test code > build prod image - push image docker hub > push project code

docker-compose -f docker-compose-dev.yml up
docker-compose -f docker-compose-dev.yml up --build
docker-compose -f docker-compose-dev.yml down

# CREATE SECRET
kubectl create secret generic pgpassword --from-literal PGPASSWORD=1323

# GKE 
  - gcloud config set project steady-petal-307322
  - gcloud config set compute/zone us-central1-c
  - gcloud container clusters get-credentials multi-cluster

# HELM
curl -fsSL -o get_helm.sh https://raw.githubusercontent.com/helm/helm/master/scripts/get-helm-3
chmod 700 get_helm.sh
./get_helm.sh

https://kubernetes.github.io/ingress-nginx/deploy/#local-development-clusters


helm repo add ingress-nginx https://kubernetes.github.io/ingress-nginx
helm install my-release ingress-nginx/ingress-nginx


# UPGRADE CLUSTER
gcloud container clusters upgrade  YOUR_CLUSTER_NAME --master --cluster-version 1.16
