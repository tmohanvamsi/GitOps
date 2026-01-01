# GitOps

- https://github.com/topics/gitops?l=smarty

# ArgoCD cli

42  argocd app get secret-appp -o yaml > app.yaml
   43  cat app.yaml 
   44  vi app.yaml 
   45  argocd app sync secret-app
   46  argocd app create -f app.yaml

- https://argo-cd.readthedocs.io/en/stable/

- kubectl port-forward -n argocd svc/argocd-server 8080:443


- docker login
sudo ctr image pull --user <dockerhub_user>:<token_or_password> docker.io/siddharth67/highway-animation:green

- docker login
sudo nerdctl pull docker.io/siddharth67/highway-animation:green


- sudo ctr image pull docker.io/siddharth67/highway-animation:blue
