# Metrics-server
>https://kubernetes.io/docs/tasks/debug/debug-cluster/resource-metrics-pipeline/

## Deploy
>Metrics-server v0.5.1
```
kubectl apply -f components.yaml
```

## Known issue
### [Fix] Failed to scrape node
```
"Failed to scrape node" err="Get \"https://192.168.1.22:10250/stats/summary?only_cpu_and_memory=true\": x509: cannot validate certificate for
```
https://blog.csdn.net/weixin_42072280/article/details/125156709

## Support
https://kubernetes.io/docs/tasks/debug/debug-cluster/resource-metrics-pipeline/
https://github.com/kubernetes-sigs/metrics-server/tree/v0.6.3
