# Testing
``
helm lint
``


# Build all dependencies
``
helm dependencies update
``

# helm install 
``
helm install sprintometer . --create-namespace --namespace=sprintometer 
``

# create yaml for deployment 
``
helm template .
``
# save  local  yaml for deployment 
``
helm template . > temp.yaml
``