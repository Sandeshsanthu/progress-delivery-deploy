# progress-delivery-deploy

first install the istioctl
kubectl label namespace progressive istio-injection=enabled --overwrite
 kubectl get analysisrun -n progressive
kubectl argo rollouts get rollout progressive-delivery -n progressive --watch
