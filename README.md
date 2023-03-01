# wils_app_by_dapinto

This repo is used in the `p3` of [this](https://github.com/RadioPotin/IOT42) repository.

The goal of the `p3` is to setup a k3d cluster with an instance of argocd running that will sync this configuration file repo with the current status of the app running on the cluster.

Expected behaviour:
When updating this repo to point towards [wil's v2 version of the app on Dockerhub](https://hub.docker.com/r/wil42/playground), argocd will fetch these new configuration requirements and redo all the deployment steps to update the app running on the cluster.

