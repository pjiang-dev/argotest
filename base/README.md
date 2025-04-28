
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/pjiang-dev/argotest.git
# cd into the cloned directory
git checkout 0f3b7b6c3abdc62301f9e7f755bd828f3ee3d329
kustomize build ./base
```