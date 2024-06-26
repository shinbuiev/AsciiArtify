Step 1. Configure network access to the administration port by running the following command:

```bash
kubectl port-forward svc/argocd-server -n argocd 8080:443&
```

Step 2. Open the URL https://127.0.0.1:8080 in your web browser.

Step 3. Install the ArgoCD CLI by following the instructions provided in the ArgoCD CLI Installation Guide https://argo-cd.readthedocs.io/en/stable/cli_installation/

Step 4. Obtain the admin password by executing the command:

```bash
argocd admin initial-password -n argocd
```
Follow any additional prompts or instructions provided to complete the setup process.

