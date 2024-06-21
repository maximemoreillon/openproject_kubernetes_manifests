# Kubernetes manifests for OpenProject installation

Those are manifests to install OpenProject on a Kubernetes cluster

NOTE: OpenProject now provides a Helm chart, making this repository irrelevant

## Usage
```
kubectl apply -f ./
```

## Configuration

Here are some settings that might require configuration:

* Database credentials in environment.yml
* NodePort in proxy.yml
