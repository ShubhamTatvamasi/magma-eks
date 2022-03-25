# magma-eks

Set kubeconfig file:
```bash
cd ~/.kube
touch orc8r.magmacore.link
export KUBECONFIG=${PWD}/orc8r.magmacore.link
```

List cluster:
```bash
aws eks list-clusters
```

Update Orc8r .kube/config:
```bash
aws eks update-kubeconfig --name orc8r
```

Update for specfic `region` using specfic `profile`:
```bash
aws eks update-kubeconfig --name orc8r \
 --region us-west-2 \
 --profile magma
```

