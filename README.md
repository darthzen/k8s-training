# Sales Training - 2018-05-31 - Kubernetes Hands-On

## Install prequisites
### Kubernetes client
```
  zypper ar https://download.opensuse.org/repositories/devel:/CaaSP:/Head:/ControllerNode/openSUSE_Leap_42.3/devel:CaaSP:Head:ControllerNode.repo
  zypper in kubernetes-client kubernetes-common
```
### Helm
```
curl https://raw.githubusercontent.com/kubernetes/helm/master/scripts/get > get_helm.sh
chmod +x get_helm.sh
./get_helm.sh

helm init --client-only
```
