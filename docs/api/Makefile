merge-yaml:  
	swagger-combine -o api_spec.yaml main.yaml

redoc-bundle:  merge-yaml 
	redoc-cli bundle -o api_spec.html api_spec.yaml
