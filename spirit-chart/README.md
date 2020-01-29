# Loan Platform Backend Helm Chart
Generic charts for deploying images to k8s cluster.

Typical usage can be found [here](https://systems.golabs.io/deployment/helm_deployment/#helm-deploy-stage).


Only tagged commits will be deployed


# How to deploy a new helm chart

1. Make a change

2. Run ./release_version.sh

3. Once you push the tag, it will be automatically deployed

4. In your app's gitalb ci, make sure upgrade the version next `--version`
e.g) 
```
--version 0.1.2
```


