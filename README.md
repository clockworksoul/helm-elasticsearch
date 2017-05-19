# helm-elasticsearch

An Elasticsearch cluster on top of Kubernetes, made easier.

A [Helm](https://github.com/kubernetes/helm) chart that essentially lifts-and-shifts the core manifests in the [pires/kubernetes-elasticsearch-cluster](https://github.com/pires/kubernetes-elasticsearch-cluster) project.

## Deploying with Helm

With Helm properly installed and configured, standing up a complete cluster is almost trivial:

```
$ git clone git@github.com:clockworksoul/helm-elasticsearch.git
$ helm install helm-elasticsearch
```

## Contributing

Please do! Taking pull requests.
