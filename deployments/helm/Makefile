.PHONY: deploy-maic
deploy-maic:
	# helm repo add bitnami https://charts.bitnami.com/bitnami
	# helm repo add codecentric https://codecentric.github.io/helm-charts
	# helm dependency update maic
	# helm dependency build maic
	helm lint --strict maic
	helm upgrade maic maic --namespace maic
