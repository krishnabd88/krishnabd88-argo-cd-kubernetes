Project Plan:

-installation of ubuntu 20.4 on the local machine.

-installation of docker-engine on ubuntu 20.4.

-installation of minikube cluster and kubectl on ubuntu 20.4.

-installation of argocd with kubectl.

-$kubectl create namespace argocd

-$kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml

-$kubectl port-forward svc/argocd-server -n argocd 8080:443

-creating GitHub repo and uploading the deployment.yaml & service.yaml file on GitHub repository. 

-login to argocd via ui http://127.0.0.1:8080

-creating a new application and connecting the GitHub repo. 

-synchronizing the application with GitHub repo and docker hub.

-minikube service todo-service --url.

-browsing IP address with port from google chrome and logging into the todo-web app.
