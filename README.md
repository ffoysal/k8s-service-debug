A simple nodejs server is runnig to print headers and paths in the console.
Helpful during debugging kubernetes service call.


```
kubectl apply -f deployment-service.yaml
```

```
kubectl run knife  --image=ffoysal/swiss-knife --restart=Never --rm -it -- sh
```

Then make `curl` to the service to see headers and paths