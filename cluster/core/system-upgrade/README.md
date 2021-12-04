# system-upgrade
### label nodes for upgrade manually
```sh
// example: kubectl label node <node-name> k3s-upgrade=true
kubectl label node k3s-node01 plan.upgrade.cattle.io/k3s=true
kubectl label node k3s-node02 plan.upgrade.cattle.io/k3s=true
kubectl label node k3s-node03 plan.upgrade.cattle.io/k3s=true
kubectl label node k3s-node04 plan.upgrade.cattle.io/k3s=true
```
