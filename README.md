# k8s-mix
Discrete information about kubernetes 

## Get the logs of kubelet

If you run kubelet using systemd, then you could use the following method to see kubelet's logs:

```console
journalctl -u kubelet
```

First, need to ssh into your node.