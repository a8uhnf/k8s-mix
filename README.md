# k8s-mix
Discrete information about kubernetes 

## Get the logs of kubelet

If using GKE cluster then needs to ssh into node and run below command.

```console
sudo journalctl -u kubelet
```