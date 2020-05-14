#

``` shell
kubectl create secret generic thanos-objectstorage --from-file=thanos.yaml=thanos-storage-minio.yaml -n ops
kubectl create secret generic tracing-config --from-file=jaeger.yaml=tracing-config.yaml -n ops

```
