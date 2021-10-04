# ./kubernetes-manifests

[![CIS](https://app.soluble.cloud/api/v1/public/badges/aaab01a9-2154-4793-886a-4eb4681b2ef7.svg)](https://app.soluble.cloud/repos/details/github.com/aleftik/k8s-files)  [![IaC](https://app.soluble.cloud/api/v1/public/badges/24fea43b-f4bd-4863-882f-477916e41bb0.svg)](https://app.soluble.cloud/repos/details/github.com/aleftik/k8s-files)  

:warning: Kubernetes manifests provided in this directory are not directly
deployable to a cluster. They are meant to be used with `skaffold` command to
insert the correct `image:` tags.

Use the manifests in [/release](/release) directory which are configured with
pre-built public images.
