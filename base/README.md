
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/pjiang-dev/argotest.git
# cd into the cloned directory
git checkout 45e60d2761e25ae38dd022b5ccc66cf735ed70f8
kustomize build ./base
```