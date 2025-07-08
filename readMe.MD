taint the node

```
kubectl taint nodes ip-192-168-31-180.ec2.internal  hardware=gpu:NoSchedule
```

Label node

```
kubectl label nodes ip-192-168-31-180.ec2.internal  hardware=gpu
```
