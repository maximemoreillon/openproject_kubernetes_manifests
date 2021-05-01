# Kubernetes manifests for OpenProject installation

Those are manifests to install OpenProject on a Kubernetes cluster

## Usage
```
kubectl apply -f ./
```

## Configuration

Here are some settings that might require configuration:

* Database password in environment.yml and postgres.yml
* NodePort in proxy.yml
