# 2048 App

## Create Fargate profile

```
eksctl create fargateprofile \
    --cluster demo-cluster \
    --region us-east-1 \
    --name alb-sample-app \
    --namespace game-2048
```

## Deploy the deployment, service and Ingress

```
kubectl apply -f https://raw.githubusercontent.com/VarunTej06/EKS-Cluster/refs/heads/main/2048-full.yaml
```



![2048](https://github.com/VarunTej06/EKS-Cluster/blob/main/Documentation/2048_enhanced.png)
