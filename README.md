helm template common --name-template emby --namespace test --dry-run  --kube-version 1.27 --values charts/global-values.yaml --values charts/stable/emby/values.yaml


helm template --release-name emby --values ../../global-values.yaml --values values.yaml .