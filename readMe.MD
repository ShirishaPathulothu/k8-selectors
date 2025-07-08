taint the node

```
kubectl taint nodes ip-192-168-23-150.ec2.internal hardware=gpu:NoSchedule
```

Label node

```
kubectl label nodes ip-192-168-23-150.ec2.internal hardware=gpu
```
