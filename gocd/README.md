## goCD and nginx demo
What you will need: minikube, kubectl and its dependencies: https://kubernetes.io/docs/tasks/tools/install-minikube/

To start your kubernetes cluster in minikube vm on your local computer
minikube start --cpus 4 --memory 8192
minikube kubectl -- apply -f demo.yaml

once all pods are up and running, check which port go-server is running on
minikube kubectl -- port-forward svc/go-server :8153
use port number of above command to access the page

demo git repository for pipelines /godata/db/config.git