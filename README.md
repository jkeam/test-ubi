# Test UBI

Test building a very simple container based on a UBI on OpenShift.

## Deploy to OpenShift

1. Update `storageClassName` in `create-pipeline.yaml` to match your storage class
2. Apply file

    ```shell
    oc apply -f ./create-pipeline.yaml
    ```
