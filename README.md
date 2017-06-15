# es-cluster-k8s

### create es image
in es2.4.5

```
docker build -t estest ./
```

### add plugin
in es-plugin
```
docker build -t 10.39.0.118/xiaoyuchen/elasticsearch:2.4.5c ./
```

### create kube petset
in yaml
```
kubectl create -f es-petset.yaml 
kubectl create -f es-petset-data.yaml 
```
