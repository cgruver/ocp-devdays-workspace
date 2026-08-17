# ocp-devdays-workspace
Workspace for contributing to OCP Dev Days project.

```bash
git remote add upstream https://github.com/rhpds/ocp-dev-days-rdshw-gitops
git fetch upstream dev
git merge upstream/dev
git push

git fetch upstream
git checkout main
git reset --hard upstream/main
git push origin main --force

```
