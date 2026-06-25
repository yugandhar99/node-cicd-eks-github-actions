# Project Review Notes

Repository: `node-cicd-eks-github-actions`

## What I cleaned or improved

- Rebuilt the main README with a career-progression story.
- Added your requested animated footer/contact section.
- No existing project screenshots were found in the uploaded source, so I added a screenshot guide under `docs/screenshots/README.md`.
- Removed old author/domain references from the workflow.
- Replaced the older container registry deployment flow with a cleaner Amazon ECR + EKS GitHub Actions workflow.
- Fixed Kustomize staging/prod container patch names so they match the base deployment container.
- Updated Terraform provider configuration to use the `region` variable instead of a hardcoded provider region.
- Added missing Terraform provider declarations for Helm, Kubernetes, and Null provider usage.
- Kept `.env`, secrets, Terraform state, kubeconfigs, and token files blocked in `.gitignore`.
- Added cleanup/cost-control commands in README.

## Review before making public

- Run the local Node.js tests before pushing.
- Run Terraform only if you are ready for temporary AWS cost.
- Add your own screenshots after running the lab.
- Do not commit real cloud credentials, tokens, kubeconfigs, private keys, `.env`, or Terraform state.
