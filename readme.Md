# Selectors
---
To Taint the node
---
kubectl taint nodes ip-192-168-33-94.ec2.internal hardware=gpu:NoSchedule
---
To Label the Node ip-192-168-33-94.ec2.internal hardware=gpu
---
Nodeselectors are also used to tolerate.. First we label the node which is tainted.the we give nodeSelector key and value that mentioned in the tainted node
Now the pod goes to the tainted node
---