## This project is no longer maintained

Dear friends and collegues. Given that the [pires/kubernetes-elasticsearch-cluster](https://github.com/pires/kubernetes-elasticsearch-cluster) repository -- the source of truth for this project -- is no longer maintained, and given that I don't have any time or energy to maintain this repository either, I've decided to cease maintaining it. I'll now archive it in hope that it can still serve some historical value.

Thank you all for your help and your support!

## helm-elasticsearch

[![Build Status](https://img.shields.io/travis/clockworksoul/helm-elasticsearch.svg?style=flat-square)](https://travis-ci.org/clockworksoul/helm-elasticsearch)

An Elasticsearch cluster on top of Kubernetes, made easier.

A [Helm](https://github.com/kubernetes/helm) chart that essentially lifts-and-shifts the core manifests in the [pires/kubernetes-elasticsearch-cluster](https://github.com/pires/kubernetes-elasticsearch-cluster) project.

## Deploying with Helm

With Helm properly installed and configured, standing up a complete cluster is almost trivial:

```
$ git clone https://github.com/clockworksoul/helm-elasticsearch.git elasticsearch
$ helm install elasticsearch
```

## Contributing

Please do! Taking pull requests.
