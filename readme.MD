# Selectors

To taint the node

```
kubectl taint nodes node1 key1=value1:NoSchedule
# for example:: kubectl taint nodes <node1> hardware=gpu:NoSchedule
```
to untaint a node
```
# kubectl taint nodes <node1> hardware=gpu:NoSchedule-
```
To Label a node
```
 kubectl label nodes <node1> hardware=gpu
```
Ref: https://kubernetes.io/docs/tasks/configure-pod-container/assign-pods-nodes
