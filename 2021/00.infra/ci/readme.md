# Concorse CI 

## Login to cli tool
```
fly -t ci login -c http://127.0.0.1:8090

fly -t ci set-pipeline -p build-and-push-image -c ./example.pipeline.yml -l vars.yml
```
