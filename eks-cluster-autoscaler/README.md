### Deploy autoscaling component

    kubectl apply -f https://raw.githubusercontent.com/kubernetes/autoscaler/master/cluster-autoscaler/cloudprovider/aws/examples/cluster-autoscaler-autodiscover.yaml

### Deploy nginx pods with service

    kubectl apply -f nginx.yaml
