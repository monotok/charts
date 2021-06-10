Helm Charts
===========

This repository is a fork from ohdearaugustin but only contains the trilium notes chart

- trilium-notes ([zadam/trilium](https://github.com/zadam/trilium))

Usage
-----
This section describes the usage of this repository.

How to add repo
***************
```
helm repo add monotok https://monotok.github.io/charts/
"monotok" has been added to your repositories
```

How to install a chart
***************
Just `helm install monotok/trilium-notes`.

For more information on using Helm, refer to the Helm documentation.

CI
--
All charts are tested on pull requests, with the following versions of Kubernetes:

- v1.17.11
- v1.18.8
- v1.19.4

This will change over the time.
