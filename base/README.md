
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/pjiang-dev/argotest.git
# cd into the cloned directory
git checkout e162bf86ffa030ccec5a7ac60555336ce92a310d
kustomize build ./base
```