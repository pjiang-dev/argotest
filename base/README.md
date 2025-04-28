
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/pjiang-dev/argotest.git
# cd into the cloned directory
git checkout a774bbf56b48c17184763a57e1e18e5138ee33b7
kustomize build ./base
```