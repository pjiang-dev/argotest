
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/pjiang-dev/argotest.git
# cd into the cloned directory
git checkout 287ac88e6f4afa31967434464955e740e50a1a91
kustomize build ./base
```