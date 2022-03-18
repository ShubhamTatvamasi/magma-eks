# magma-eks

List cluster:
```bash
aws eks list-clusters
```

Update Orc8r .kube/config:
```bash
aws eks update-kubeconfig --name orc8r
```

Update for specfic region using specfic profile:
```bash
aws eks update-kubeconfig --name orc8r \
 --region us-west-2 \
 --profile magma
```

