# Helm

https://github.com/helm/helm/releases

INSTALL FROM SOURCE:<br>
    In Terminal type:<br>
        - git clone https://github.com/helm/helm.git <br>
        - cd helm <br>
        - make <br>
        - helm repo add stable https://charts.helm.sh/stable <br>
        - helm repo add prometheus-community https://prometheus-community.github.io/helm-charts <br>
        - helm search repo prometheus-community <br>
        - helm install stable prometheus-community/kube-prometheus-stack <br>
