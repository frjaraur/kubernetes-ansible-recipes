minikube start --driver=kvm2  \
--addons=ingress \
--cni calico \
--memory=4096 \
--dns-proxy=false \
--host-dns-resolver=true \
--kubernetes-version=v1.22.7 \
--feature-gates=NonPreemptingPriority=true