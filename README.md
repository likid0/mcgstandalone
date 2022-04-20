# mcgstandalone
Repot to deploy ODF Multi-Cloud Gateway standalone using an argoCD application

If you don't have a running instance of argocd on your OCP cluster you can run
the setup.sh script available in the repo, it will setup a basic
openshift-gitops instance with the mcg application.

1. Fork the repo 'https://github.com/likid0/mcgstandalone'
2. Make modifications as needed to the argocd deployment.
```
vi argocd/values.yaml
```
3. Make modifications to the MCG configuration as needed.
```
vi argocd/mcg.yaml
```
4. Push the modifications to your forked github repo.
5. run the setup.sh script.
```
bash setup.sh
```
